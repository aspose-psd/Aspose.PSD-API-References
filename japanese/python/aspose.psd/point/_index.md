---
title: "Point クラス"
type: docs
weight: 3530
url: /ja/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Point()](#Point__1) | Point クラスの新しいインスタンスを初期化します。 |
| [Point(dw)](#Point_dw_2) | 整数値で指定された座標を使用して、[Point](/psd/python-net/aspose.psd/point/) 構造体の新しいインスタンスを初期化します。 |
| [Point(size)](#Point_size_3) | [Size](/psd/python-net/aspose.psd/size/) 構造体から [Point](/psd/python-net/aspose.psd/point/) 構造体の新しいインスタンスを初期化します。 |
| [Point(x, y)](#Point_x_y_4) | 指定された座標で [Point](/psd/python-net/aspose.psd/point/) 構造体の新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | [Point.x](/psd/python-net/aspose.psd/point/) と [Point.y](/psd/python-net/aspose.psd/point/) の値が 0 に設定された [Point](/psd/python-net/aspose.psd/point/) 構造体の新しいインスタンスを取得します。 |
| is_empty | bool | r | この [Point](/psd/python-net/aspose.psd/point/) が空かどうかを示す値を取得します。 |
| x | int | r/w | この [Point](/psd/python-net/aspose.psd/point/) の x 座標を取得または設定します。 |
| y | int | r/w | この [Point](/psd/python-net/aspose.psd/point/) の y 座標を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | 指定された [Size](/psd/python-net/aspose.psd/size/) を指定された [Point](/psd/python-net/aspose.psd/point/) に加算します。 |
| [ceiling(point)](#ceiling_point_2) | 指定された [PointF](/psd/python-net/aspose.psd/pointf/) の値を次の整数に切り上げて、[Point](/psd/python-net/aspose.psd/point/) に変換します。 |
| [offset(dx, dy)](#offset_dx_dy_3) | 指定された量だけこの [Point](/psd/python-net/aspose.psd/point/) を平行移動します。 |
| [offset(point)](#offset_point_4) | 指定された [Point](/psd/python-net/aspose.psd/point/) だけこの [Point](/psd/python-net/aspose.psd/point/) を平行移動します。 |
| [round(point)](#round_point_5) | 指定された [PointF](/psd/python-net/aspose.psd/pointf/) を、[Point](/psd/python-net/aspose.psd/point/) の値を最も近い整数に丸めて、[Point](/psd/python-net/aspose.psd/point/) オブジェクトに変換します。 |
| [subtract(point, size)](#subtract_point_size_6) | 指定された [Size](/psd/python-net/aspose.psd/size/) を指定された [Point](/psd/python-net/aspose.psd/point/) から減算した結果を返します。 |
| [truncate(point)](#truncate_point_7) | 指定された [PointF](/psd/python-net/aspose.psd/pointf/) を、[Point](/psd/python-net/aspose.psd/point/) の値を切り捨てて [Point](/psd/python-net/aspose.psd/point/) に変換します。 |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Point クラスの新しいインスタンスを初期化します。

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

整数値で指定された座標を使用して、[Point](/psd/python-net/aspose.psd/point/) 構造体の新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dw | int | 新しいポイントの座標を指定する 32 ビット整数です。 |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

[Size](/psd/python-net/aspose.psd/size/) 構造体から [Point](/psd/python-net/aspose.psd/point/) 構造体の新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | 新しいポイントの座標を含みます。 |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

指定された座標で [Point](/psd/python-net/aspose.psd/point/) 構造体の新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | 点の水平位置。 |
| y | int | 点の垂直位置。 |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

指定された [Size](/psd/python-net/aspose.psd/size/) を指定された [Point](/psd/python-net/aspose.psd/point/) に加算します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 追加先の [Point](/psd/python-net/aspose.psd/point/)。 |
| size | [Size](/psd/python-net/aspose.psd/size) | 追加先の <paramref name="point" /> に対する [Size](/psd/python-net/aspose.psd/size/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 加算操作の結果となる [Point](/psd/python-net/aspose.psd/point/)。 |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

指定された [PointF](/psd/python-net/aspose.psd/pointf/) の値を次の整数に切り上げて、[Point](/psd/python-net/aspose.psd/point/) に変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 変換対象の [PointF](/psd/python-net/aspose.psd/pointf/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | このメソッドが変換する先の [Point](/psd/python-net/aspose.psd/point/)。 |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

指定された量だけこの [Point](/psd/python-net/aspose.psd/point/) を平行移動します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dx | int | x 座標をオフセットする量です。 |
| dy | int | y 座標をオフセットする量です。 |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

指定された [Point](/psd/python-net/aspose.psd/point/) だけこの [Point](/psd/python-net/aspose.psd/point/) を平行移動します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | この [Point](/psd/python-net/aspose.psd/point/) をオフセットするために使用される [Point](/psd/python-net/aspose.psd/point/)。 |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

指定された [PointF](/psd/python-net/aspose.psd/pointf/) を、[Point](/psd/python-net/aspose.psd/point/) の値を最も近い整数に丸めて、[Point](/psd/python-net/aspose.psd/point/) オブジェクトに変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 変換対象の [PointF](/psd/python-net/aspose.psd/pointf/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | このメソッドが変換する先の [Point](/psd/python-net/aspose.psd/point/)。 |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

指定された [Size](/psd/python-net/aspose.psd/size/) を指定された [Point](/psd/python-net/aspose.psd/point/) から減算した結果を返します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 減算される対象の [Point](/psd/python-net/aspose.psd/point/)。 |
| size | [Size](/psd/python-net/aspose.psd/size) | <paramref name="point" /> から減算される [Size](/psd/python-net/aspose.psd/size/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | 減算操作の結果となる [Point](/psd/python-net/aspose.psd/point/)。 |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

指定された [PointF](/psd/python-net/aspose.psd/pointf/) を、[Point](/psd/python-net/aspose.psd/point/) の値を切り捨てて [Point](/psd/python-net/aspose.psd/point/) に変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 変換対象の [PointF](/psd/python-net/aspose.psd/pointf/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | このメソッドが変換する先の [Point](/psd/python-net/aspose.psd/point/)。 |


