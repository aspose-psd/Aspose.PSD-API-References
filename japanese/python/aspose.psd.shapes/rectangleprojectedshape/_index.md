---
title: "RectangleProjectedShape クラス"
type: docs
weight: 70
url: /ja/python-net/aspose.psd.shapes/rectangleprojectedshape/
---

**Summary:** Represents a shape which is projected over rectangle turned to a particular orientation.<br/>            Specified by four points which can be rotated in space maintaining the same edges length and 90 degrees between adjacent edges.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.RectangleProjectedShape

**Inheritance:** Shape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | オブジェクトの境界を取得します。 |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | シェイプの中心を取得します。 |
| has_segments | bool | r | シェイプがセグメントを持つかどうかを示す値を取得します。 |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 左下の矩形ポイントを取得します。 |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 左上の矩形ポイントを取得します。 |
| rectangle_height | double | r | 矩形の高さを取得します。 |
| rectangle_width | double | r | 矩形の幅を取得します。 |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 右下の矩形ポイントを取得します。 |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 右上の矩形ポイントを取得します。 |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | シェイプのセグメントを取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | オブジェクトの境界を取得します。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | オブジェクトの境界を取得します。 |
| [transform(transform)](#transform_transform_3) | 指定された変換をシェイプに適用します。 |


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

