---
title: "TextShape 클래스"
type: docs
weight: 90
url: /ko/python-net/aspose.psd.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [TextShape()](#TextShape__1) | 새 인스턴스를 초기화합니다 [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) 클래스. |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | 새 인스턴스를 초기화합니다 [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | 객체의 경계를 가져옵니다. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | 도형의 중심을 가져옵니다. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r/w | 텍스트를 그리는 데 사용되는 폰트를 가져오거나 설정합니다. |
| has_segments | bool | r | 도형에 세그먼트가 있는지 여부를 나타내는 값을 가져옵니다. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 왼쪽 아래 사각형 점을 가져옵니다. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 왼쪽 위 사각형 점을 가져옵니다. |
| rectangle_height | double | r | 사각형 높이를 가져옵니다. |
| rectangle_width | double | r | 사각형 너비를 가져옵니다. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | 오른쪽 아래 사각형 점을 가져옵니다. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | 오른쪽 위 사각형 점을 가져옵니다. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | 도형 세그먼트를 가져옵니다. |
| text | 문자열 | r/w | 그려진 텍스트를 가져오거나 설정합니다. |
| text_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r/w | 텍스트 형식을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 객체의 경계를 가져옵니다. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 객체의 경계를 가져옵니다. |
| [transform(transform)](#transform_transform_3) | 지정된 변환을 도형에 적용합니다. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

새 인스턴스를 초기화합니다 [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) 클래스.

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

새 인스턴스를 초기화합니다 [TextShape](/psd/python-net/aspose.psd.shapes/textshape/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| text | 문자열 | 그릴 텍스트. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 텍스트 사각형. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | 사용할 폰트. |
| string_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | 문자열 형식. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

객체의 경계를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 경계 이전에 적용할 행렬이 계산됩니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 예상 객체의 경계입니다. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

객체의 경계를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 경계 이전에 적용할 행렬이 계산됩니다. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | 객체에 사용할 펜입니다. 이는 객체의 경계 크기에 영향을 줄 수 있습니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 예상 객체의 경계입니다. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

지정된 변환을 도형에 적용합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | 적용할 변환입니다. |

