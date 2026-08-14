---
title: "TextShape クラス"
type: docs
weight: 90
url: /ja/python-net/aspose.psd.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [TextShape()](#TextShape__1) | 新しい [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) クラスのインスタンスを初期化します。 |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | 新しい [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | オブジェクトの境界を取得します。 |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | シェイプの中心を取得します。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r/w | テキストの描画に使用するフォントを取得または設定します。 |
| has_segments | bool | r | シェイプがセグメントを持つかどうかを示す値を取得します。 |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 左下の矩形ポイントを取得します。 |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 左上の矩形ポイントを取得します。 |
| rectangle_height | double | r | 矩形の高さを取得します。 |
| rectangle_width | double | r | 矩形の幅を取得します。 |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 右下の矩形ポイントを取得します。 |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 右上の矩形ポイントを取得します。 |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | シェイプのセグメントを取得します。 |
| text | string | r/w | 描画されたテキストを取得または設定します。 |
| text_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r/w | テキストの書式を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | オブジェクトの境界を取得します。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | オブジェクトの境界を取得します。 |
| [transform(transform)](#transform_transform_3) | 指定された変換をシェイプに適用します。 |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

新しい [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) クラスのインスタンスを初期化します。

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

新しい [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| text | string | 描画するテキストです。 |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | テキスト矩形です。 |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 使用するフォントです。 |
| string_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 文字列の書式です。 |

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

