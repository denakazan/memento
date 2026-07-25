---
title: "Day12: 波のエネルギー(運動エネルギーと弾性エネルギー)"
date: 2026-07-26
excerpt: "線密度μの弦を張力Sで張ったときに伝わる波の、運動エネルギーと弾性エネルギーについてまとめました。"
---

線密度 $\mu$ の弦を、張力 $S$ で張った状態を考える。弦の横方向の変位を $y(x,t)$ とする。

## 運動エネルギー

微小長さ $dx$ の要素は横方向に速度 $\partial y/\partial t$ で運動しているので、運動エネルギー密度(単位長さあたり)は

$$
\frac{dK}{dx} = \frac{1}{2} \mu \left( \frac{\partial y}{\partial t} \right)^2
$$

## 弾性エネルギー(位置エネルギー)

弦が伸びることで蓄えられるエネルギー。傾き $\partial y/\partial x$ が小さいとして近似すると、弾性エネルギー密度は

$$
\frac{dU}{dx} = \frac{1}{2} S \left( \frac{\partial y}{\partial x} \right)^2
$$

## 進行波での全エネルギー

$y = A \sin(kx - \omega t)$ のような進行波では、$\partial y/\partial t = -A\omega \cos(kx-\omega t)$、$\partial y/\partial x = Ak\cos(kx-\omega t)$ となる。波の速度は $v = \omega/k = \sqrt{S/\mu}$ なので $Sk^2 = \mu \omega^2$ となり、運動エネルギー密度と弾性エネルギー密度は常に等しい(エネルギーの等分配)。

全エネルギー密度の時間平均は

$$
\left\langle \frac{dK}{dx} + \frac{dU}{dx} \right\rangle = \frac{1}{2} \mu \omega^2 A^2
$$

これに波の速度 $v$ をかけると、波が運ぶ平均仕事率(パワー)になる。

$$
P = \frac{1}{2} \mu \omega^2 A^2 v
$$
