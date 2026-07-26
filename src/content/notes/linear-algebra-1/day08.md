---
title: "Day08: 逆行列、行列のべき乗"
date: 2026-05-19
excerpt: "逆行列の定義と2次正方行列の逆行列の公式、行列のべき乗についてまとめました。"
---

## 逆行列

正方行列 $A$ に対して

$$
AA^{-1} = A^{-1}A = I
$$

を満たす行列 $A^{-1}$ を $A$ の逆行列という。逆行列が存在する行列を正則行列という。

## 2次正方行列の逆行列

$$
A = \begin{pmatrix} a & b \\\\ c & d \end{pmatrix}
$$

のとき

$$
A^{-1} = \frac{1}{ad-bc} \begin{pmatrix} d & -b \\\\ -c & a \end{pmatrix}
$$

($ad-bc \ne 0$ のときに限り存在する)。

## 行列のべき乗

$$
A^n = \underbrace{A \cdot A \cdots A}_{n\text{個}}, \qquad A^0 = I
$$

正方行列どうしの積なので、べき乗が定義できる。
