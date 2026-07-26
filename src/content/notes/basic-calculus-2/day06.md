---
title: "Day06: 部分積分2(定積分)"
date: 2026-10-06
excerpt: "定積分の部分積分公式と、境界項[fg]の扱い方についてまとめました。"
---

定積分でも同様に部分積分できる。

$$
\int_a^b f(x) g'(x) dx = \big[f(x) g(x)\big]_a^b - \int_a^b f'(x) g(x) dx
$$

原始関数のときと違い、右辺に境界項 $\big[fg\big]_a^b = f(b)g(b) - f(a)g(a)$ が加わる点に注意する。

## 例

$$
\int_0^1 x e^x dx = \big[x e^x\big]_0^1 - \int_0^1 e^x dx = (e - 0) - (e-1) = 1
$$
