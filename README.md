# 環境構築

## リポジトリ

- 地域通貨アプリ用フロントエンド

## FW

- vue.js

## 命名ルール

- 変数名: camelCase
- メソッド名: camelCase
- ファイル名: camelCase
- ディレクトリ名: camelCase

## 前提

- git 等の諸々の作業は完了している前提

## 手順

1. `docker compose build`を実行
1. `docker compose run --rm client bash`を実行
1. client コンテナ内で`yarn install`を実行し、モジュールインストール後コンテナから出る
1. `docker compose up`を実行
1. `localhost`にアクセスし、vue の初期画面を確認

## LIFF Inspector（動作確認用プラグインの使用方法）
LIFF Inspectorは、LIFFアプリをデバッグするためのLIFFプラグインです。
LIFF Inspectorを使うと、LIFFアプリを実行している端末とは別のPC上のChrome DevTools (opens new window)を使って、LIFFアプリをデバッグできます。


[こちらの記事](https://zenn.dev/arahabica/articles/c86e425db7b898#liff%E3%82%A2%E3%83%97%E3%83%AA%E3%81%AE%E3%83%87%E3%83%90%E3%83%83%E3%82%B0
)を参考に動作確認をお願いします。
