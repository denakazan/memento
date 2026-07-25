---
title: "Day04: 極座標による2重積分"
date: 2026-07-26
excerpt: "直交座標の2重積分を極座標に変換するときのヤコビアン(rの因子)についてまとめました。"
---

領域 $D$ 上の2重積分を、極座標 $x = r\cos\theta$, $y = r\sin\theta$ に変換すると

$$
\iint_D f(x, y) \ dx \ dy = \iint_{D'} f(r\cos\theta, r\sin\theta) \ r \ dr \ d\theta
$$

ここで因子 $r$ はヤコビアン $\left| \dfrac{\partial(x,y)}{\partial(r,\theta)} \right|$ から出てくる。
