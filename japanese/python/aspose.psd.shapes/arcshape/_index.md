---
title: "ArcShape クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | 新しい [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) クラスのインスタンスを初期化します。 |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | 新しい [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) クラスのインスタンスを初期化します。 |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | 新しい [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | オブジェクトの境界を取得します。 |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | シェイプの中心を取得します。 |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | 終了シェイプポイントを取得します。 |
| has_segments | bool | r | シェイプがセグメントを持つかどうかを示す値を取得します。 |
| is_closed | bool | r/w | 順序付けられたシェイプが閉じているかどうかを示す値を取得または設定します。閉じた順序付けシェイプを処理する場合、開始点と終了点に意味はありません。 |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 左下の矩形ポイントを取得します。 |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 左上の矩形ポイントを取得します。 |
| rectangle_height | double | r | 矩形の高さを取得します。 |
| rectangle_width | double | r | 矩形の幅を取得します。 |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 右下の矩形ポイントを取得します。 |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 右上の矩形ポイントを取得します。 |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | シェイプのセグメントを取得します。 |
| start_angle | float | r/w | 開始角度を取得または設定します。 |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | 開始シェイプポイントを取得します。 |
| sweep_angle | float | r/w | スイープ角度を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | オブジェクトの境界を取得します。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | オブジェクトの境界を取得します。 |
| reverse() | このシェイプのポイントの順序を逆にします。 |
| [transform(transform)](#transform_transform_3) | 指定された変換をシェイプに適用します。 |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

新しい [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) クラスのインスタンスを初期化します。

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

新しい [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形。 |
| start_angle | float | 開始角度です。 |
| sweep_angle | float | スイープ角度です。 |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

新しい [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形。 |
| start_angle | float | 開始角度です。 |
| sweep_angle | float | スイープ角度です。 |
| is_closed | bool | <c>true</c> に設定すると、円弧が閉じます。閉じた円弧は実際には楕円に縮退します。 |

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

