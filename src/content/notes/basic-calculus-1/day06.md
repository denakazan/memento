---
title: "Day06: 三角関数の微分"
date: 2026-05-11
excerpt: "sin, cos, tanの微分公式とその導き方についてまとめました。"
---

## 基本公式

$$
\frac{d}{dx}\sin x = \cos x, \qquad \frac{d}{dx}\cos x = -\sin x
$$

$\sin x$ を微分すると $\cos x$、さらに微分すると $-\sin x$、というように4回微分すると元に戻る。

## tan xの微分

$\tan x = \sin x / \cos x$ に商の微分公式を使うと

$$
\frac{d}{dx}\tan x = \frac{\cos x \cdot \cos x - \sin x \cdot (-\sin x)}{\cos^2 x} = \frac{\cos^2 x + \sin^2 x}{\cos^2 x} = \frac{1}{\cos^2 x}
$$

$\sin^2 x + \cos^2 x = 1$ を使って分子を簡単にしている。
