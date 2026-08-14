---
title: "SizeF クラス"
type: docs
weight: 4090
url: /ja/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [SizeF()](#SizeF__1) | SizeF クラスの新しいインスタンスを初期化します |
| [SizeF(point)](#SizeF_point_2) | 指定された[PointF](/psd/python-net/aspose.psd/pointf/)から[SizeF](/psd/python-net/aspose.psd/sizef/)構造の新しいインスタンスを初期化します。 |
| [SizeF(size)](#SizeF_size_3) | 指定された[SizeF](/psd/python-net/aspose.psd/sizef/)から[SizeF](/psd/python-net/aspose.psd/sizef/)構造の新しいインスタンスを初期化します。 |
| [SizeF(width, height)](#SizeF_width_height_4) | 指定された寸法から[SizeF](/psd/python-net/aspose.psd/sizef/)構造の新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | [SizeF.width](/psd/python-net/aspose.psd/sizef/) と [SizeF.height](/psd/python-net/aspose.psd/sizef/) の値が 0 に設定された[SizeF](/psd/python-net/aspose.psd/sizef/)構造の新しいインスタンスを取得します。 |
| height | float | r/w | この[SizeF](/psd/python-net/aspose.psd/sizef/)の垂直成分を取得または設定します。 |
| is_empty | bool | r | この[SizeF](/psd/python-net/aspose.psd/sizef/)の幅と高さがゼロかどうかを示す値を取得します。 |
| width | float | r/w | この[SizeF](/psd/python-net/aspose.psd/sizef/)の水平成分を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | ある[SizeF](/psd/python-net/aspose.psd/sizef/)構造の幅と高さを別の[SizeF](/psd/python-net/aspose.psd/sizef/)構造の幅と高さに加算します。 |
| [subtract(size1, size2)](#subtract_size1_size2_2) | ある[SizeF](/psd/python-net/aspose.psd/sizef/)構造の幅と高さを別の[SizeF](/psd/python-net/aspose.psd/sizef/)構造の幅と高さから減算します。 |
| [to_point_f()](#to_point_f__3) | [SizeF](/psd/python-net/aspose.psd/sizef/) を [PointF](/psd/python-net/aspose.psd/pointf/) に変換します。 |
| [to_size()](#to_size__4) | [SizeF](/psd/python-net/aspose.psd/sizef/) を切り捨てられたサイズ値を持つ[Size](/psd/python-net/aspose.psd/size/)構造に変換します。 |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

SizeF クラスの新しいインスタンスを初期化します

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

指定された[PointF](/psd/python-net/aspose.psd/pointf/)から[SizeF](/psd/python-net/aspose.psd/sizef/)構造の新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | この[SizeF](/psd/python-net/aspose.psd/sizef/)を初期化するための[PointF](/psd/python-net/aspose.psd/pointf/)。 |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

指定された[SizeF](/psd/python-net/aspose.psd/sizef/)から[SizeF](/psd/python-net/aspose.psd/sizef/)構造の新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 新しい[SizeF](/psd/python-net/aspose.psd/sizef/)を作成する元となる[SizeF](/psd/python-net/aspose.psd/sizef/)。 |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

指定された寸法から[SizeF](/psd/python-net/aspose.psd/sizef/)構造の新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| width | float | 新しい[SizeF](/psd/python-net/aspose.psd/sizef/)の幅成分。 |
| height | float | 新しい[SizeF](/psd/python-net/aspose.psd/sizef/)の高さ成分。 |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

ある[SizeF](/psd/python-net/aspose.psd/sizef/)構造の幅と高さを別の[SizeF](/psd/python-net/aspose.psd/sizef/)構造の幅と高さに加算します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | 最初の [SizeF](/psd/python-net/aspose.psd/sizef/) を追加します。 |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | 2番目の [SizeF](/psd/python-net/aspose.psd/sizef/) を追加します。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | 加算操作の結果となる [SizeF](/psd/python-net/aspose.psd/sizef/) 構造体です。 |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

ある[SizeF](/psd/python-net/aspose.psd/sizef/)構造の幅と高さを別の[SizeF](/psd/python-net/aspose.psd/sizef/)構造の幅と高さから減算します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | 減算演算子の左側にある [SizeF](/psd/python-net/aspose.psd/sizef/) 構造体です。 |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | 減算演算子の右側にある [SizeF](/psd/python-net/aspose.psd/sizef/) 構造体です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | 減算操作の結果となる [SizeF](/psd/python-net/aspose.psd/sizef/) です。 |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

[SizeF](/psd/python-net/aspose.psd/sizef/) を [PointF](/psd/python-net/aspose.psd/pointf/) に変換します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | [PointF](/psd/python-net/aspose.psd/pointf/) 構造体を返します。 |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

[SizeF](/psd/python-net/aspose.psd/sizef/) を切り捨てられたサイズ値を持つ[Size](/psd/python-net/aspose.psd/size/)構造に変換します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | [Size](/psd/python-net/aspose.psd/size/) 構造体を返します。 |


