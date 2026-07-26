---
title: "Day07: 重積分(7); 3重積分、体積(円柱座標・球座標)"
date: 2026-08-11
excerpt: "対称性のよい立体の体積計算に便利な、円柱座標・球座標での3重積分をまとめました。"
---

直交座標のままでは計算しにくい立体でも、対称性に合わせた座標系に変換すると積分しやすくなる。

## 円柱座標

$x = r\cos\theta$、$y = r\sin\theta$、$z=z$ とすると、体積要素は

$$
dV = r dr d\theta dz
$$

## 球座標

$x = r\sin\phi\cos\theta$、$y = r\sin\phi\sin\theta$、$z = r\cos\phi$ とすると、体積要素は

$$
dV = r^2 \sin\phi dr d\theta d\phi
$$

球のように原点からの距離だけで境界が決まる立体の体積計算に向いている。
