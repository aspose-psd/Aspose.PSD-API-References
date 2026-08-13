---
title: "فئة TextShape"
type: docs
weight: 90
url: /ar/python-net/aspose.psd.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TextShape()](#TextShape__1) | ينشئ مثيلًا جديدًا من الفئة [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | ينشئ مثيلًا جديدًا من الفئة [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | يحصل على حدود الكائن. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على مركز الشكل. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r/w | يحصل أو يضبط الخط المستخدم لرسم النص. |
| has_segments | bool | r | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة الزاوية السفلية اليسرى للمستطيل. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة الزاوية العلوية اليسرى للمستطيل. |
| rectangle_height | double | r | يحصل على ارتفاع المستطيل. |
| rectangle_width | double | r | يحصل على عرض المستطيل. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة الزاوية السفلية اليمنى للمستطيل. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | يحصل على نقطة الزاوية العلوية اليمنى للمستطيل. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | يحصل على مقاطع الشكل. |
| text | string | r/w | يحصل أو يضبط النص المرسوم. |
| text_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r/w | يحصل أو يضبط تنسيق النص. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | يحصل على حدود الكائن. |
| [transform(transform)](#transform_transform_3) | يطبق التحويل المحدد على الشكل. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

ينشئ مثيلًا جديدًا من الفئة [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

ينشئ مثيلًا جديدًا من الفئة [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| text | string | النص المراد رسمه. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | مستطيل النص. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | الخط المراد استخدامه. |
| string_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | تنسيق السلسلة. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

يحصل على حدود الكائن.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | سيتم حساب المصفوفة التي ستُطبق قبل الحدود. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | حدود الكائن المقدرة. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

يحصل على حدود الكائن.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | سيتم حساب المصفوفة التي ستُطبق قبل الحدود. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | القلم المستخدم للكائن. يمكن أن يؤثر ذلك على حجم حدود الكائن. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | حدود الكائن المقدرة. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

يطبق التحويل المحدد على الشكل.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | التحويل الذي سيُطبق. |

