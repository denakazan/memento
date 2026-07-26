---
title: "Day07: 逆関数の微分、逆三角関数の微分"
date: 2026-05-18
excerpt: "逆関数の微分公式と、それを使って導く逆三角関数の微分公式についてまとめました。"
---

## 逆関数の微分

$y = f(x)$ の逆関数を $x = f^{-1}(y)$ とすると

$$
\frac{dx}{dy} = \frac{1}{dy/dx} = \frac{1}{f'(x)}
$$

元の関数の微分の逆数になる。

## 逆三角関数の微分

$$
\frac{d}{dx}\arcsin x = \frac{1}{\sqrt{1-x^2}}, \qquad \frac{d}{dx}\arccos x = -\frac{1}{\sqrt{1-x^2}}, \qquad \frac{d}{dx}\arctan x = \frac{1}{1+x^2}
$$

例えば $y = \arcsin x$ は $x = \sin y$ の逆関数なので、$dx/dy = \cos y$ となり

$$
\frac{dy}{dx} = \frac{1}{\cos y} = \frac{1}{\sqrt{1-\sin^2 y}} = \frac{1}{\sqrt{1-x^2}}
$$

のように逆関数の微分公式から導ける。
