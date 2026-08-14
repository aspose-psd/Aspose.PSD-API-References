---
title: "Figure クラス"
type: docs
weight: 1220
url: /ja/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Figure()](#Figure__1) | Figure クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | オブジェクトの境界を取得または設定します。 |
| is_closed | bool | r/w | この図形が閉じているかどうかを示す値を取得または設定します。閉じた図形は、最初と最後の図形の形状が連続した形状である場合にのみ意味があります。<br/>            最初と最後の図形の形状が連続した形状である場合、<br/>            最初の形状の最初の点は、最後の形状の最後の点から直線で接続されます。 |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | 図形全体のセグメントを取得します。 |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | 図形の形状を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | 図にシェイプを追加します。 |
| [add_shapes(shapes)](#add_shapes_shapes_2) | 図にシェイプの範囲を追加します。 |
| [get_bounds(matrix)](#get_bounds_matrix_3) | オブジェクトの境界を取得します。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | オブジェクトの境界を取得します。 |
| [remove_shape(shape)](#remove_shape_shape_5) | 図からシェイプを削除します。 |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | 図からシェイプの範囲を削除します。 |
| reverse() | この図のシェイプ順序とシェイプのポイント順序を逆にします。 |
| [transform(transform)](#transform_transform_7) | 指定された変換をシェイプに適用します。 |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Figure クラスの新しいインスタンスを初期化します。

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

図にシェイプを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | 追加するシェイプ。 |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

図にシェイプの範囲を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | 追加するシェイプ。 |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

図からシェイプを削除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | 削除するシェイプ。 |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

図からシェイプの範囲を削除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | 削除するシェイプの範囲。 |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

指定された変換をシェイプに適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | 適用する変換です。 |

