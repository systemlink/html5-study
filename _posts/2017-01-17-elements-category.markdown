---
layout: post
title:  "要素の種類"
date:   2017-01-17
categories: html5
---

## 重要ポイント

- ブロックレベル要素・インライン要素という分類はない
- 新しい７種類のカテゴリがある
- 新しいコンテンツ・モデルに、トランスペアレントが追加

## ７種類のカテゴリ

![新しい要素]({{site.baseurl}}/images/2017-01-17/element-category.png)

- インライン要素はPhrasing content（文章内コンテンツ）とほぼ同様

## コンテンツ・モデル

HTMLの内容として入れられるコンテンツが要素ごとに決められており、それをコンテンツ・モデルと呼ぶ

## トランスペアレント

コンテンツ・モデル上、透明なもののように扱われるもの  
親要素のコンテンツ・モデルがそのまま自分のコンテンツ・モデルになる特別な要素

#### 例

- a要素
- ins要素
- del要素
- object要素
- audio要素
- video要素
- canvas要素
- map要素

## Heading content(見出しコンテンツ)

h1〜h6のみ

## Sectioning content(セクションコンテンツ)

文章を区切るやつ

- article
- aside
- nav
- section

## Phrasing content(文章内コンテンツ)

ほぼ元々インライン要素だったやつ

## Embedded content(組み込みコンテンツ)

他のリソースを埋め込むやつ

- audio
- canvas
- embed
- iframe
- img
- object
- video

## Interactive content(対話型コンテンツ)

ユーザーの操作に対応するやつ

- a
- audio
- button
- embed
- iframe
- img
- input
- keygen
- label
- object
- select
- textarea
- video

## Metadata content(文書情報コンテンツ)

文書情報や他の文書との関係を定義するやつ

- base
- link
- meta
- noscript
- script
- style
- template
- title
