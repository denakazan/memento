---
title: "Day11: 偏導関数、全微分、連鎖公式、高階偏導関数"
date: 2026-06-15
excerpt: "多変数関数の偏導関数・全微分・連鎖公式と、高階偏導関数(混合偏導関数)についてまとめました。"
---

## 偏導関数

2変数関数 $f(x,y)$ を、片方の変数だけ動かして微分したもの。

$$
\frac{\partial f}{\partial x} = \lim_{h \to 0} \frac{f(x+h, y) - f(x,y)}{h}
$$

($y$ を定数とみなして $x$ について微分する。$\partial f/\partial y$ も同様)

## 全微分

$x$、$y$ がそれぞれ微小変化 $dx$、$dy$ したときの $f$ の変化量の1次近似。

$$
df = \frac{\partial f}{\partial x} dx + \frac{\partial f}{\partial y} dy
$$

## 連鎖公式(合成関数の微分)

$x = x(t)$、$y = y(t)$ のとき

$$
\frac{df}{dt} = \frac{\partial f}{\partial x}\frac{dx}{dt} + \frac{\partial f}{\partial y}\frac{dy}{dt}
$$

## 高階偏導関数

偏導関数をさらに偏微分したもの。$2$回の偏微分の順序を変えても、通常の関数では結果が一致する。

$$
\frac{\partial^2 f}{\partial x \partial y} = \frac{\partial^2 f}{\partial y \partial x}
$$
