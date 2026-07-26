---
title: "Day03: スカラー場とベクトル場、勾配、発散、回転"
date: 2026-07-11
excerpt: "スカラー場・ベクトル場の定義と、そこから作られる勾配・発散・回転(grad, div, rot)についてまとめました。"
---

## スカラー場・ベクトル場

空間の各点にスカラーを対応させるものをスカラー場($\phi(x,y,z)$ など)、ベクトルを対応させるものをベクトル場($\mathbf{F}(x,y,z)$ など)という。

## 勾配(grad)

スカラー場 $\phi$ から作られるベクトル場。

$$
\nabla \phi = \left(\frac{\partial \phi}{\partial x}, \frac{\partial \phi}{\partial y}, \frac{\partial \phi}{\partial z}\right)
$$

$\phi$ が最も急に増加する方向を向き、大きさはその方向の変化率に等しい。

## 発散(div)

ベクトル場 $\mathbf{F}$ から作られるスカラー場。

$$
\nabla \cdot \mathbf{F} = \frac{\partial F_x}{\partial x} + \frac{\partial F_y}{\partial y} + \frac{\partial F_z}{\partial z}
$$

その点でベクトル場が「湧き出している」度合いを表す。

## 回転(rot, curl)

ベクトル場 $\mathbf{F}$ から作られるベクトル場。

$$
\nabla \times \mathbf{F} = \left(\frac{\partial F_z}{\partial y} - \frac{\partial F_y}{\partial z},\ \frac{\partial F_x}{\partial z} - \frac{\partial F_z}{\partial x},\ \frac{\partial F_y}{\partial x} - \frac{\partial F_x}{\partial y}\right)
$$

その点でのベクトル場の「渦」の強さと軸の向きを表す。
