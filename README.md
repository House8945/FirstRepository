---
marp: true
theme: default
header: "目次のための欄､現在位置を黒字に"
footer: "引用のための欄"
headingDivider: 1
paginate: true
size: 4:3
math: katex
style: |
  section::after {
    content: attr(data-marpit-pagination) " / " attr(data-marpit-pagination-total);
  }
---

# Markdown 資料サンプル

---
<!--
class: heading
-->
## 見出し

### 小見出し

#### さらに小さい見出し

---

## 2. 強調

<!--
class: right_bottom
-->
**太字**  
*斜体*  
***太字かつ斜体***

---

## 3. 箇条書きリスト

<!--
class: lists
-->
- りんご
- みかん
  - オレンジ
  - マンダリン
- バナナ

---

## 4. 番号付きリスト

1. 朝起きる
   1. 目を開ける
   2. ベッドから降りる
2. 顔を洗う
   1. 勇気を出す
      1. 水を掬う

---

## 6. リンク・画像

[OpenAI公式サイト](https://openai.com)

![サンプル画像](https://placehold.jp/24/cc9999/993333/200x100.png?text=Sample+Image)

---

## 7. 引用
<!--
class: paragraph
-->
> Markdownは、シンプルな記号で文書を装飾できる便利なツールです。  

---

## 8. コード

### インラインコード

`print("Hello, Markdown!")`

### コードブロック

```python
def greet(name):
    print(f"Hello, {name}!")

greet("Markdown")
```

---

## 表
|`code`    |*italic*                  |
|----------|--------------------------|
|**bold**  |***bold italic***         |
|$\omega$|[Qiita](http://qiita.com)|