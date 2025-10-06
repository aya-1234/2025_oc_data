---
marp: true
theme: gaia
footer: '**madonomori**'
---

新規スライド

![bg left](pic/_1080468.jpg)

---

# 目次

1. はじめに
2. アプリについて

---

| アプリとは | 必要な理由 | 行動 |
| ---------- | ---------- | ---- |
| あ<br />   |            |      |

---

`"aaa"`

`` `バッククオート` `` や ` ``2連続バッククオート`` ` も記述できます。

---

# これは H1 タグです

## これは H2 タグです

###### これは H6 タグです

---

打ち消し線を使うには ~~ で囲みます。 ~~打ち消し~~

---

<!-- open属性なし -->

<details><summary>サンプルコード（open属性なし）</summary>

```rb
puts 'Hello, World'
```

</details>

<!-- open属性あり -->

<details open><summary>サンプルコード（open属性あり）</summary>

```rb
puts 'Hello, World'
```

</details>

---

- `\*

* `+

- `-

---

1. a
2. b
3. c

---

| 名前       | マークダウン記法 | 例    |
| ---------- | ---------------- | ----- |
| ボールド   | \*\* \*\*        | **a** |
| イタリック | \_ \_            | _a_   |
| コード     | ` `              | `aaa` |
| リンク     | [text](url)      |       |

---

- [ ] タスク 1
- [x] タスク 2

---

> 文頭に>を置くことで引用になります。
> 複数行にまたがる場合、改行のたびにこの記号を置く必要があります。
> **引用の上下にはリストと同じく空行がないと正しく表示されません**
> 引用の中に別の Markdown を使用することも可能です。
>
> > これはネストされた引用です。

---

全ては苦戦を引く

今回の場合ページの変更に使用

```
* * *
***
*****
- - -
---------------------------------------

```

---

リンクの挿入

[Qiita](http://qiita.com 'Qiita Home')

[ここ][link-1]()と [この][link-1]() リンクは同じになります。
[link-1](http://qiita.com/)という書き方もできます。

[link-1](http://qiita.com/)

---

## タイトルありの画像を埋め込む

![bg left](pic/_1080468.jpg)("画像タイトル")

## タイトル無しの画像を埋め込む

![bg right](pic/_1080468.jpg)

---

<img width=50 src="pic/_1080468.jpg">

---

| Left align | Right align | Center align |
| :--------- | ----------: | :----------: |
| This       |        This |     This     |
| column     |      column |    column    |
| will       |        will |     will     |
| be         |          be |      be      |
| left       |       right |    center    |
| aligned    |     aligned |   aligned    |

---

```math
\left( \sum_{k=1}^n a_k b_k \right)^{\!\!2} \leq
\left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```

---

$a = \\{1, 2, 3\\}$

---

https://qiita.com/Qiita/items/c686397e4a0f4f11683d

---

コードブロックの言語名を plantuml とすることで、PlantUML によるダイアグラムを表示することができます。

```plantuml
Bob->Alice : Hello!
```

---

コードブロックの言語名を mermaid とすることで、Mermaid によるダイアグラムを表示することができます。

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
