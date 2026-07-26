---
title: "Day08: 重積分(8); 曲面積"
date: 2026-08-17
excerpt: "z=f(x,y)で表される曲面の表面積を、2重積分を使って求める公式についてまとめました。"
---

$xy$平面上の領域 $D$ の上にある曲面 $z=f(x,y)$ の表面積は

$$
S = \iint_D \sqrt{1 + \left(\frac{\partial f}{\partial x}\right)^2 + \left(\frac{\partial f}{\partial y}\right)^2} dx dy
$$

曲面が平坦($\partial f/\partial x = \partial f/\partial y = 0$)なら、これは単に領域 $D$ の面積 $\iint_D dx dy$ に一致する。傾きが急な部分ほど、平面に投影したときより実際の表面積が大きくなることを、ルートの中の項が表している。
