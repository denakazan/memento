---
title: "Day11: 無理関数の積分2"
date: 2026-11-10
excerpt: "sqrt(x^2+a^2)やsqrt(x^2-a^2)型の無理関数を、三角関数や双曲線関数への置換で積分する方法をまとめました。"
---

## sqrt(x^2 + a^2) 型

$x = a\tan\theta$ とおくと $\sqrt{x^2+a^2} = a/\cos\theta$ になり、根号を外せる。

## sqrt(x^2 - a^2) 型

$x = a/\cos\theta$ とおく、または双曲線関数を使って $x = a\cosh t$ とおくと、$\sqrt{x^2-a^2} = a\sinh t$ になり根号を外せる。

## 例

$$
\int \frac{1}{\sqrt{x^2+a^2}} dx = \ln\left(x + \sqrt{x^2+a^2}\right) + C
$$

いずれの型も、置換によって三角関数(または双曲線関数)の積分に帰着させるのが基本方針。
