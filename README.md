# Vue-Django Connection for Token Authentication

DjangoやVueを連携してToken認証を実装するログインアプリを開発する方法を詳細に解説する。

# 環境構築

まずは、以下のコマンドを入力する

```
pip install django
pip install django-rest-framework
pip install djoser
pip install django-cors-headers
```

これで開発に必要なパッケージやライブラリはインストール完了。

# Djangoプロジェクトの作成

```
django-admin startproject backend
```

一応、インストールの確認のため以下のコマンドで開発者サーバを立ち上げる。

```
py manage.py runserver
```

何も問題がなければインストールは完了。


# 開発環境

* Visual Studio Code
* Python
* Django REST Framework
* Django
* Djoser
* Vue.js
* Vue CLI

