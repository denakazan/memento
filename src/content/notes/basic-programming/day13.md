---
title: "Day13: 構造体とファイルの分割"
date: 2026-06-29
excerpt: "型の異なるデータをまとめるC言語の構造体と、ヘッダファイルを使ったコードの分割方法についてまとめました。"
---

## 構造体

複数のデータをひとまとめにして扱うための型。

```c
struct Point {
    int x;
    int y;
};

struct Point p;
p.x = 1;
p.y = 2;
```

## ファイルの分割

プログラムが大きくなると、1つのファイルにまとめず、複数のファイルに分割する。

- `.h`(ヘッダファイル): 関数のプロトタイプ宣言や構造体の定義を書く
- `.c`(ソースファイル): 実際の処理(関数の中身)を書く

```c
// point.h
struct Point { int x; int y; };
int distance(struct Point a, struct Point b);
```

```c
// point.c
#include "point.h"

int distance(struct Point a, struct Point b) {
    int dx = a.x - b.x;
    int dy = a.y - b.y;
    return dx * dx + dy * dy;
}
```

他のファイルから使うときは `#include "point.h"` のようにヘッダファイルを読み込む。
