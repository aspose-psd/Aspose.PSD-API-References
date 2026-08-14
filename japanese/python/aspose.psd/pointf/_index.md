---
title: "PointF クラス"
type: docs
weight: 3550
url: /ja/python-net/aspose.psd/pointf/
---

**Summary:** Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.PointF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PointF()](#PointF__1) | 新しい PointF クラスのインスタンスを初期化します |
| [PointF(x, y)](#PointF_x_y_2) | 指定された座標で新しい [PointF](/psd/python-net/aspose.psd/pointf/) 構造体のインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| empty [static] | [PointF](/psd/python-net/aspose.psd/pointf) | r | [PointF.x](/psd/python-net/aspose.psd/pointf/) と [PointF.y](/psd/python-net/aspose.psd/pointf/) の値が 0 に設定された新しい [PointF](/psd/python-net/aspose.psd/pointf/) 構造体のインスタンスを取得します。 |
| is_empty | bool | r | この [PointF](/psd/python-net/aspose.psd/pointf/) が空かどうかを示す値を取得します。 |
| x | float | r/w | この [PointF](/psd/python-net/aspose.psd/pointf/) の x 座標を取得または設定します。 |
| y | float | r/w | この [PointF](/psd/python-net/aspose.psd/pointf/) の y 座標を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | 指定された [Size](/psd/python-net/aspose.psd/size/) だけ与えられた [PointF](/psd/python-net/aspose.psd/pointf/) を平行移動します。 |
| [add(point, size)](#add_point_size_2) | 指定された [Size](/psd/python-net/aspose.psd/size/) だけ与えられた [PointF](/psd/python-net/aspose.psd/pointf/) を平行移動します。 |
| [subtract(point, size)](#subtract_point_size_3) | 指定されたサイズの負の値だけ [PointF](/psd/python-net/aspose.psd/pointf/) を平行移動します。 |
| [subtract(point, size)](#subtract_point_size_4) | 指定されたサイズの負の値だけ [PointF](/psd/python-net/aspose.psd/pointf/) を平行移動します。 |


### Constructor: PointF() {#PointF__1}


```
 PointF() 
```

新しい PointF クラスのインスタンスを初期化します

### Constructor: PointF(x, y) {#PointF_x_y_2}


```
 PointF(x, y) 
```

指定された座標で新しい [PointF](/psd/python-net/aspose.psd/pointf/) 構造体のインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | float | 点の水平位置。 |
| y | float | 点の垂直位置。 |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

指定された [Size](/psd/python-net/aspose.psd/size/) だけ与えられた [PointF](/psd/python-net/aspose.psd/pointf/) を平行移動します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 変換する対象の [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| size | [Size](/psd/python-net/aspose.psd/size) | 座標 <paramref name=\"point\" /> に加える数値を指定する [Size](/psd/python-net/aspose.psd/size/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | 変換された [PointF](/psd/python-net/aspose.psd/pointf/)。 |


### Method: add(point, size)  [static] {#add_point_size_2}


```
 add(point, size) 
```

指定された [Size](/psd/python-net/aspose.psd/size/) だけ与えられた [PointF](/psd/python-net/aspose.psd/pointf/) を平行移動します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 変換する対象の [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 座標 <paramref name=\"point\" /> に加える数値を指定する [Size](/psd/python-net/aspose.psd/size/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | 変換された [PointF](/psd/python-net/aspose.psd/pointf/)。 |


### Method: subtract(point, size)  [static] {#subtract_point_size_3}


```
 subtract(point, size) 
```

指定されたサイズの負の値だけ [PointF](/psd/python-net/aspose.psd/pointf/) を平行移動します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 変換する対象の [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| size | [Size](/psd/python-net/aspose.psd/size) | 座標 <paramref name=\"point\" /> から減算する数値を指定する [Size](/psd/python-net/aspose.psd/size/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | 変換された [PointF](/psd/python-net/aspose.psd/pointf/)。 |


### Method: subtract(point, size)  [static] {#subtract_point_size_4}


```
 subtract(point, size) 
```

指定されたサイズの負の値だけ [PointF](/psd/python-net/aspose.psd/pointf/) を平行移動します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 変換する対象の [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 座標 <paramref name=\"point\" /> から減算する数値を指定する [Size](/psd/python-net/aspose.psd/size/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | 変換された [PointF](/psd/python-net/aspose.psd/pointf/)。 |


