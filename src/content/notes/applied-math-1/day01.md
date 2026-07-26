---
title: "Day01: ベクトル、内積、外積、スカラー3重積、ベクトル3重積"
date: 2026-07-08
excerpt: "ベクトルの内積・外積、スカラー3重積・ベクトル3重積の定義と幾何学的な意味をまとめました。"
---

## ベクトル

大きさと向きを持つ量。成分表示では $\mathbf{a} = (a_1, a_2, a_3)$ のように書く。

## 内積(スカラー積)

$$
\mathbf{a} \cdot \mathbf{b} = a_1b_1 + a_2b_2 + a_3b_3 = |\mathbf{a}||\mathbf{b}|\cos\theta
$$

結果はスカラー。$\theta$ は2つのベクトルのなす角。

## 外積(ベクトル積)

$$
\mathbf{a} \times \mathbf{b} = (a_2b_3 - a_3b_2,\ a_3b_1 - a_1b_3,\ a_1b_2 - a_2b_1)
$$

結果はベクトルで、$\mathbf{a}$、$\mathbf{b}$ の両方に垂直な向き(右手系)を持つ。大きさ $|\mathbf{a}||\mathbf{b}|\sin\theta$ は、2つのベクトルが張る平行四辺形の面積に等しい。

## スカラー3重積

$$
\mathbf{a} \cdot (\mathbf{b} \times \mathbf{c})
$$

結果はスカラーで、3つのベクトルが張る平行六面体の体積(符号付き)に等しい。

## ベクトル3重積

$$
\mathbf{a} \times (\mathbf{b} \times \mathbf{c}) = \mathbf{b}(\mathbf{a} \cdot \mathbf{c}) - \mathbf{c}(\mathbf{a} \cdot \mathbf{b})
$$

いわゆるBAC-CAB則と呼ばれる展開公式。
