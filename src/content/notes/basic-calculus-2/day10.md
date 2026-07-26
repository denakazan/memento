---
title: "Day10: 無理関数の積分1"
date: 2026-11-03
excerpt: "平方根を含む無理関数を、三角関数への置換によって積分しやすい形に変換する方法をまとめました。"
---

$\sqrt{a^2-x^2}$ のような形を含む積分は、三角関数による置換で根号を外せる。

## sqrt(a^2 - x^2) 型

$x = a\sin\theta$ とおくと $\sqrt{a^2-x^2} = a\cos\theta$($-\pi/2 \le \theta \le \pi/2$)。

$$
\int \sqrt{a^2-x^2} dx = \int a\cos\theta \cdot a\cos\theta \ d\theta = a^2\int \cos^2\theta \ d\theta
$$

三角関数の積分(半角公式など)に帰着させて計算する。

## 例

$$
\int_0^a \sqrt{a^2-x^2} dx
$$

は半径 $a$ の円の4分の1の面積を表しており、$x=a\sin\theta$ の置換で計算すると $\dfrac{\pi a^2}{4}$ になる。
