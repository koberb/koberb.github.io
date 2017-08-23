# koberb.github.io

is built with [Middleman](https://middlemanapp.com/jp/)!

## 開発フロー

### 環境構築

1. `.ruby-version` に書いてあるRubyをインストールする
2. このリポジトリをcloneして、 `bundle install`

### サーバー起動

```
$ bundle exec middleman
```

### ブランチ戦略

Default Branchが `middleman` なので、ここにコミットするかPR作成してください。

### デプロイ

下記コマンド実行すると、masterブランチでbuildされ、pushまで動きます。

```
$ bundle exec middleman deploy --build-before
```
