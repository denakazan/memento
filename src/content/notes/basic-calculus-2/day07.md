---
title: "Day07: 広義積分"
date: 2026-10-13
excerpt: "積分区間が無限に広がる場合や被積分関数が発散する場合の広義積分(極限による定義)についてまとめました。"
---

## 積分区間が非有界な場合

$$
\int_a^{\infty} f(x) dx = \lim_{R \to \infty} \int_a^R f(x) dx
$$

右辺の極限が有限の値に収束するとき、広義積分は収束するという。

## 被積分関数が発散する場合

例えば $x=a$ で $f(x)$ が発散するとき

$$
\int_a^b f(x) dx = \lim_{\varepsilon \to 0^+} \int_{a+\varepsilon}^b f(x) dx
$$

のように、発散点を避けた区間で積分してから極限を取る。

## 例

$$
\int_1^{\infty} \frac{1}{x^2} dx = \lim_{R \to \infty} \big[-\tfrac{1}{x}\big]_1^R = \lim_{R \to \infty} \left(1 - \frac{1}{R}\right) = 1
$$
