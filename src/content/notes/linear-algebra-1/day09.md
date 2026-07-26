---
title: "Day09: 1次変換"
date: 2026-05-26
excerpt: "行列を使ってベクトルを別のベクトルに対応させる1次変換と、回転行列・拡大縮小行列の例をまとめました。"
---

## 1次変換

行列 $A$ を使って、ベクトル $\mathbf{x}$ に $\mathbf{x}' = A\mathbf{x}$ を対応させる変換を1次変換(線形変換)という。和とスカラー倍を保つ($A(\mathbf{x}+\mathbf{y}) = A\mathbf{x}+A\mathbf{y}$、$A(k\mathbf{x}) = kA\mathbf{x}$)という性質を持つ。

## 回転行列

平面上で原点を中心に角 $\theta$ だけ回転させる1次変換。

$$
R(\theta) = \begin{pmatrix} \cos\theta & -\sin\theta \\\\ \sin\theta & \cos\theta \end{pmatrix}
$$

## 拡大縮小行列

$x$ 方向に $k_1$ 倍、$y$ 方向に $k_2$ 倍する1次変換。

$$
\begin{pmatrix} k_1 & 0 \\\\ 0 & k_2 \end{pmatrix}
$$
