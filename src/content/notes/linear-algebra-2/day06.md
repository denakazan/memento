---
title: "Day06: 行列の固有値と対角化(1) 固有値と固有ベクトル"
date: 2026-05-13
excerpt: "固有値・固有ベクトルの定義と、特性方程式det(A-λI)=0から固有値を求める方法についてまとめました。"
---

## 固有値・固有ベクトルの定義

零ベクトルでないベクトル $\mathbf{v}$ と定数 $\lambda$ が

$$
A\mathbf{v} = \lambda \mathbf{v}
$$

を満たすとき、$\lambda$ を $A$ の固有値、$\mathbf{v}$ をその固有値に対応する固有ベクトルという。$A$ をかけても向きが変わらず、大きさだけ $\lambda$ 倍されるベクトル、というイメージ。

## 特性方程式

$A\mathbf{v} = \lambda \mathbf{v}$ を $(A-\lambda I)\mathbf{v} = \mathbf{0}$ と変形すると、$\mathbf{v} \ne \mathbf{0}$ の解を持つためには $A-\lambda I$ が正則でない必要がある。つまり

$$
\det(A - \lambda I) = 0
$$

(特性方程式)。これを $\lambda$ について解くと固有値が求まり、各固有値を代入した $(A-\lambda I)\mathbf{v}=\mathbf{0}$ を解くと対応する固有ベクトルが求まる。
