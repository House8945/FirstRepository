---
marp: true
theme: base
paginate: true
size: 4:3
math: katex
---
<!--
_class: title
-->
**Markdown 資料サンプル**
<a>私です｡</a>

---
<!--
_header: <b>背景</b> 目的 手段 結果 考察
-->
# 1. 見出し

## 小見出し

### さらに小さい見出し

本文だよ


---
<!--
_header: 背景 <b>目的</b> 手段 結果 考察
-->
# 2. 強調

**太字**  
*斜体*  
***太字かつ斜体***
~~打ち消し線~~


---
# 3. 箇条書きリスト

- りんご
- みかん
  - オレンジ
  - マンダリン
- バナナ


---
# 4. 番号付きリスト

1. 朝起きる
   1. 目を開ける
   2. ベッドから降りる
2. 顔を洗う
   1. 勇気を出す
      1. 水を掬う


---
# 6. リンク・画像

[OpenAI公式サイト](https://openai.com)

![サンプル画像](https://placehold.jp/24/cc9999/993333/200x100.png?text=Sample+Image)


---
# 7. 引用

> P.J. Marlow, & B.L. Anderson: "Material properties derived fromthree-dimensional shape representations", Vis. Res., 115, Part B,pp.199-208（2015）


---
# 8. コード

## インラインコード
`print("Hello, Markdown!")`

## コードブロック
```python
def greet(name):
    print(f"Hello, {name}!")

greet("Markdown")
```


---
## 表
|`code`    |*italic*                  |
|:--|:-:|
|**bold**  |***bold italic***         |
|$\omega$|[Qiita](http://qiita.com)|