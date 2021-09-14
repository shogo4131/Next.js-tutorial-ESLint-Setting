---
title: "ESLint Setting"
date: "2021-09-08"
---

# .eslintrc.js 設定一覧

## env

- よく使うものだけ true にしておく
- 設定しすぎると ESLint が重くなるので必要なものだけ設定する

## extends

- extends は複数指定できるので配列にしておく
- 一番効かせたいのは最後に記述する
- Prettier の設定と被せないため記述しておく
- rules で上書きできる

## plugins

- ESlint のプラグインをインストールして指定する

## rules

- ルールを設定する(セミコロン等)

## setting

- React の version エラー等を検知する設定が書ける
