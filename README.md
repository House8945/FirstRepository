---
marp: true
theme: default
header: "こんにちは"
footer: "さようなら"
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
## 見出し

### 小見出し

#### さらに小さい見出し

---

## 2. 強調

**太字**  
*斜体*  
***太字かつ斜体***

---

## 3. 箇条書きリスト

- りんご
- みかん
  - オレンジ
  - マンダリン
- バナナ

---

## 4. 番号付きリスト

1. 朝起きる
2. 顔を洗う
3. 朝ごはんを食べる

---

## 6. リンク・画像

[OpenAI公式サイト](https://openai.com)

![サンプル画像](https://placehold.jp/24/cc9999/993333/200x100.png?text=Sample+Image)

---

## 7. 引用

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