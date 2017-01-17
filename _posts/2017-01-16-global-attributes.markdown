---
layout: post
title:  "グローバル属性"
date:   2017-01-16
categories: html5
---

## グローバル属性

すべての要素に共通して指定できる属性

#### 一覧

- class
- id
- lang
- title
- style
- dir（列挙属性：ltr,rtl,auto）
- tabindex
- accesskey
- hidden（論理属性）
- translate（列挙属性：yes,no）
- spellcheck（列挙属性：true,false）
- contenteditable（列挙属性：true,false）

`論理属性` は値が省略できる。逆に言うと指定しても何もおきない  
`列挙属性` は入力する値が決まっている

## HTML5で追加されたやつ

### hidden

<div>
  <p>=> 表示するやつ</p>
</div>
<div hidden>
  <p>=> 表示しないやつ</p>
</div>

```
<div>
  <p>表示するやつ</p>
</div>
<div hidden>
  <p>表示しないやつ</p>
</div>
```

### translate

Chrome使って日本語に翻訳すると結果が見える

<p translate="yes">
Please translate here
</p>
<pre>
  <code translate="no">
    console.log("Please translate here");
  </code>
</pre>

```
<p translate="yes">
Please translate here
</p>
<pre>
  <code translate="no">
    console.log("Please translate here");
  </code>
</pre>
```

### spellcheck / contenteditable

フォーカスが当たったときの動作を確認

<p><input type="text" spellcheck="true" value="This is a sampl."></p>
<p><input type="text" spellcheck="false" value="This is a sampl."></p>
<p contenteditable="true" spellcheck="true">This is a sampl.</p>
<p contenteditable="true" spellcheck="false">This is a sampl.</p>
<p contenteditable="false" spellcheck="true">This is a sampl.</p>

```
<p><input type="text" spellcheck="true" value="This is a sampl."></p>
<p><input type="text" spellcheck="false" value="This is a sampl."></p>
<p contenteditable="true" spellcheck="true">This is a sampl.</p>
<p contenteditable="true" spellcheck="false">This is a sampl.</p>
<p contenteditable="false" spellcheck="true">This is a sampl.</p>
```