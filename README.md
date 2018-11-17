# Docker-Jupyter

## original image

* jupyter/tensorflow-notebook    
	https://hub.docker.com/r/jupyter/tensorflow-notebook/

 ## インストール

* jupyter notebook ~~5.7.0~~ 5.6.0

## 作業フォルダ

* `./Docker-Jupyter/Jupyter/src`

## 使い方

1. `docker-compose up -d` : コンテナ起動する

1. `docker-compose logs` : トークンを確認する(token=xxxxxxxx)

1. ブラウザで`http://127.0.0.1:8888/?token=xxxxxxxx`にアクセスする

1. 事前に確認しておいた`token`を入力し、ログインする

## 停止方法

1. `docker-compose down` : 停止する
