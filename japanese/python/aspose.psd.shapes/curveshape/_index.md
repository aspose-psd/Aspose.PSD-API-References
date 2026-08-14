---
title: "CurveShape クラス"
type: docs
weight: 30
url: /ja/python-net/aspose.psd.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | 新しい [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) クラスのインスタンスを初期化します。 |
| [CurveShape(points)](#CurveShape_points_2) | 新しい [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) クラスのインスタンスを初期化します。デフォルトのテンション 0.5 が使用されます。 |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | 新しい [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) クラスのインスタンスを初期化します。デフォルトのテンション 0.5 が使用されます。 |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | 新しい [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) クラスのインスタンスを初期化します。 |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | 新しい [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | オブジェクトの境界を取得します。 |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | シェイプの中心を取得します。 |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | 終了シェイプポイントを取得します。 |
| has_segments | bool | r | シェイプがセグメントを持つかどうかを示す値を取得します。 |
| is_closed | bool | r/w | シェイプが閉じているかどうかを示す値を取得または設定します。 |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | 曲線ポイントを取得または設定します。 |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | シェイプのセグメントを取得します。 |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | 開始シェイプポイントを取得します。 |
| テンション | float | r/w | 曲線のテンションを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | オブジェクトの境界を取得します。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | オブジェクトの境界を取得します。 |
| reverse() | このシェイプのポイントの順序を逆にします。 |
| [transform(transform)](#transform_transform_3) | 指定された変換をシェイプに適用します。 |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

新しい [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) クラスのインスタンスを初期化します。

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

新しい [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) クラスのインスタンスを初期化します。デフォルトのテンション 0.5 が使用されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | ポイント配列です。 |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

新しい [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) クラスのインスタンスを初期化します。デフォルトのテンション 0.5 が使用されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | ポイント配列です。 |
| is_closed | bool | <c>true</c> に設定すると、曲線が閉じます。 |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

新しい [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | ポイント配列です。 |
| テンション | float | 曲線のテンションです。 |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

新しい [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | ポイント配列です。 |
| テンション | float | 曲線のテンションです。 |
| is_closed | bool | <c>true</c> に設定すると、曲線が閉じます。 |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

オブジェクトの境界を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 境界の前に適用する行列が計算されます。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 推定されたオブジェクトの境界。 |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

オブジェクトの境界を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 境界の前に適用する行列が計算されます。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | オブジェクトに使用するペンです。これによりオブジェクトの境界サイズに影響を与える可能性があります。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 推定されたオブジェクトの境界。 |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

指定された変換をシェイプに適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | 適用する変換です。 |

