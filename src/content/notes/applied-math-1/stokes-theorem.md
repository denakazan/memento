---
title: "ストークスの定理"
date: 2026-07-24
excerpt: "ベクトル解析におけるストークスの定理の数式表現"
---

ストークスの定理は、曲面上の回転(rot)の面積分と、その境界に沿った線積分を結びつける定理。

$$
\oint_{\partial \Sigma} \mathbf{F} \cdot d\mathbf{r} = \iint_{\Sigma} (\nabla \times \mathbf{F}) \cdot d\mathbf{S}
$$

Markdown中でLaTeXの数式を書くときは `\( ... \)` や `\[ ... \]` は使えない(Markdownのバックスラッシュエスケープ処理で `\(` `\[` などの記号がバックスラッシュごと消えてしまう)。インラインは `$...$`、ディスプレイは `$$...$$` を使うこと。
