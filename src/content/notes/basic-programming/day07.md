---
title: "Day07: 整列アルゴリズム、時間計測"
date: 2026-05-18
excerpt: "配列を並び替える整列アルゴリズム(選択ソート・バブルソート)と、実行時間を計測する方法についてまとめました。"
---

## 選択ソート

未整列部分から最小値を探し、先頭と交換する、を繰り返す。

```java
for (int i = 0; i < a.length - 1; i++) {
    int minIndex = i;
    for (int j = i + 1; j < a.length; j++) {
        if (a[j] < a[minIndex]) {
            minIndex = j;
        }
    }
    int tmp = a[i];
    a[i] = a[minIndex];
    a[minIndex] = tmp;
}
```

## バブルソート

隣り合う要素を比較して、順序が逆なら交換する、を配列の端まで繰り返す。

```java
for (int i = 0; i < a.length - 1; i++) {
    for (int j = 0; j < a.length - 1 - i; j++) {
        if (a[j] > a[j + 1]) {
            int tmp = a[j];
            a[j] = a[j + 1];
            a[j + 1] = tmp;
        }
    }
}
```

## 時間計測

処理の前後の時刻を記録し、差を取ることで実行時間を測れる。

```java
long start = System.nanoTime();
// 計測したい処理
long end = System.nanoTime();
System.out.println((end - start) + " ns");
```
