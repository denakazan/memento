---
title: "Day02: 分岐と反復、数値積分"
date: 2026-04-13
excerpt: "if文・for文などの分岐と反復の基本構文と、それを使った区分求積法による数値積分の例をまとめました。"
---

## 分岐

条件によって実行する処理を切り替える。

```java
if (x >= 0) {
    System.out.println("非負");
} else {
    System.out.println("負");
}
```

## 反復

同じ処理を繰り返す。

```java
for (int i = 0; i < 10; i++) {
    System.out.println(i);
}
```

## 数値積分(区分求積法)

定積分 $\int_a^b f(x) dx$ を、幅の小さい長方形の面積の和で近似する。

```java
double a = 0.0, b = 1.0;
int n = 1000;
double h = (b - a) / n;
double sum = 0.0;
for (int i = 0; i < n; i++) {
    double x = a + i * h;
    sum += f(x) * h;
}
```

分割数 `n` を大きくするほど、真の積分値に近づく。
