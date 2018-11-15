FROM jupyter/tensorflow-notebook
RUN pip uninstall -y notebook
RUN pip install notebook==5.6.0
RUN pip install jupyter_contrib_nbextensions
RUN jupyter contrib nbextension install --user
RUN jupyter nbextension enable codefolding/main
COPY ./conf/notebook.json /home/jovyan/.jupyter/nbconfig/
CMD [ "/opt/conda/bin/jupyter", "notebook" ]
