---
title: "ObjectWithBounds クラス"
type: docs
weight: 3170
url: /ja/python-net/aspose.psd/objectwithbounds/
---

**Summary:** The object having bounds.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | オブジェクトの境界を取得します。 |
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

