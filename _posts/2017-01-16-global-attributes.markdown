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
- dir
- tabindex
- accesskey
- hidden
- translate
- spellcheck
- contenteditable

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
  <p>表示するやつ</p>
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