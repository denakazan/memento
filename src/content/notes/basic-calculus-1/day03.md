---
title: "Day03: 分数関数と無理式の微分"
date: 2026-04-20
excerpt: "べき乗の微分公式を負の指数・分数の指数に拡張して、分数関数と無理式を微分する方法をまとめました。"
---

べき乗の微分公式

$$
\frac{d}{dx} x^n = n x^{n-1}
$$

は、$n$ が負の整数や分数のときにも成り立つ。

## 分数関数の微分

$$
\frac{d}{dx} \frac{1}{x^n} = \frac{d}{dx} x^{-n} = -n x^{-n-1} = -\frac{n}{x^{n+1}}
$$

## 無理式の微分

$$
\frac{d}{dx} \sqrt[n]{x} = \frac{d}{dx} x^{1/n} = \frac{1}{n} x^{\frac{1}{n} - 1}
$$

例えば $\sqrt{x} = x^{1/2}$ の微分は

$$
\frac{d}{dx} \sqrt{x} = \frac{1}{2} x^{-1/2} = \frac{1}{2\sqrt{x}}
$$
