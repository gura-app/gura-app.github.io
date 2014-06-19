---
layout: page
lang: ja
title: デジカメ写真取り込みアプリ Getter Photo
---

# {{ page.title }}

## アプリケーションの紹介

Getter Photo は、デジカメで撮影した画像ファイルをパソコンに取り込むアプリケーションです。

* 撮影日付ごとにフォルダを作成します。
* 画像ファイルを撮影日時をもとにしたファイル名にしてコピーします。


## 動作環境

Windows が動作している PC を用意してください。Windows 7 で動作確認しています。それ以前のバージョン Windows XP、Vista でも大丈夫だと思いますが、Windows 8 は未確認です。

このアプリケーションを実行するには [Gura プログラミング言語](http://www.gura-lang.org/)
の環境が必要です。[ダウンロードページ](http://www.gura-lang.org/Download.html) から
Windows Installer (`gura-x.x.x-win32.msi`) をダウンロードし、インストールしてください。


## インストール

パッケージファイル [getterphoto-1.0.0.zip](https://github.com/gura-app/getterphoto/releases/download/v1.0.0/getterphoto-1.0.0.zip)
をダウンロードして適当なフォルダに展開します。

エキスプローラなどでスクリプトファイル `getterphoto.guraw` をダブルクリックするとプログラムが起動します。

デスクトップにアイコンを作りたい場合はスクリプトファイル `setup.guraw` を起動してください。
`[セットアップ]` ボタンをクリックするとセットアップを行います。


## 使い方




## 開発者むけ情報

このアプリケーションは GitHub レポジトリで管理されています。
以下のコマンドでレポジトリを取得することができます。

    git clone https://github.com/gura-app/getterphoto.git
