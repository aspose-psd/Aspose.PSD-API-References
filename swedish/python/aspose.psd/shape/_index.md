---
title: "Shape-klass"
type: docs
weight: 4020
url: /sv/python-net/aspose.psd/shape/
---

**Summary:** The shape. A continuous set of points connected using a specific rule.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Shape

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Hämtar objektets gränser. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar formens centrum. |
| has_segments | bool | r | Hämtar ett värde som indikerar om formen har segment. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Hämtar formens segment. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Hämtar objektets gränser. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Hämtar objektets gränser. |
| [transform(transform)](#transform_transform_3) | Tillämpar den angivna transformationen på formen. |


### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriserna som ska tillämpas innan gränser beräknas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Det uppskattade objektets gränser. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriserna som ska tillämpas innan gränser beräknas. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Pennan som ska användas för objektet. Detta kan påverka objektets gränsstorlek. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Det uppskattade objektets gränser. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Tillämpar den angivna transformationen på formen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Transformationen att tillämpa. |

