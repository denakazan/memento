---
title: "Day12: 三角関数の積分1"
date: 2026-11-17
excerpt: "sin・cosのべき乗の積分を、半角公式や積和公式を使って計算する方法をまとめました。"
---

## 半角公式を使う方法

$\sin^2\theta$、$\cos^2\theta$ が含まれる積分は、半角公式で次数を下げてから積分する。

$$
\sin^2\theta = \frac{1-\cos 2\theta}{2}, \qquad \cos^2\theta = \frac{1+\cos 2\theta}{2}
$$

## 積和公式を使う方法

$\sin$、$\cos$ の積の形($\sin A \cos B$ など)は、積和公式で和の形に直すと積分しやすくなる。

$$
\sin A \cos B = \frac{1}{2}\big(\sin(A+B) + \sin(A-B)\big)
$$

## 例

$$
\int \sin^2 x \ dx = \int \frac{1-\cos 2x}{2} dx = \frac{x}{2} - \frac{\sin 2x}{4} + C
$$
