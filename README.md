# README
# Rails 6 アプリテンプレート (React版)

React による開発環境を組み込んだ、 Rails 6 の新規アプリテンプレートです。トップページは、 home#index のルーティングになっていて、Reactが動くコードがテストで書いてあります。

セットアップについては、まずは [basicテンプレートのほう](https://github.com/yncat/rails-template-basic) を読んで、DBなどの設定をしてください。Rails s する直前までいったら、以下の追加タスクを実行してください。

## 追加タスク
$ bundle ex rails webpacker:install:react

## You're on rails!

react-rails というgemを入れているので、 bundle ex rails g react:component とかすると、新しいコンポーネントを作れます。詳細は、 react-rails のリファレンスを参照してください。

とりあえず以上です。
