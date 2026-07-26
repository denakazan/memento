---
title: "Day01: 原始関数"
date: 2026-09-01
excerpt: "微分すると元の関数に戻る原始関数(不定積分)の定義と、基本的な原始関数の一覧をまとめました。"
---

## 原始関数

$F'(x) = f(x)$ を満たす関数 $F(x)$ を、$f(x)$ の原始関数という。原始関数は定数の違いを除いて一意に決まる(2つの原始関数の差は定数)。

$$
\int f(x) dx = F(x) + C
$$

($C$: 積分定数)を $f(x)$ の不定積分という。

## 基本的な原始関数

$$
\int x^n dx = \frac{x^{n+1}}{n+1} + C \ (n \ne -1), \qquad \int \frac{1}{x} dx = \ln|x| + C
$$

$$
\int e^x dx = e^x + C, \qquad \int \sin x \ dx = -\cos x + C, \qquad \int \cos x \ dx = \sin x + C
$$
