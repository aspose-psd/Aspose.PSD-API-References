---
title: "ArcShape-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Initierar en ny instans av klassen [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Initierar en ny instans av klassen [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Initierar en ny instans av klassen [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Hämtar objektets gränser. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar formens centrum. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar den avslutande formpunkten. |
| has_segments | bool | r | Hämtar ett värde som indikerar om formen har segment. |
| is_closed | bool | r/w | Hämtar eller anger ett värde som indikerar om den ordnade formen är sluten. Vid bearbetning av en sluten ordnad form har start- och slutpunkterna ingen betydelse. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar rektangelns nedre vänstra punkt. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar rektangelns övre vänstra punkt. |
| rectangle_height | double | r | Hämtar rektangelns höjd. |
| rectangle_width | double | r | Hämtar rektangelns bredd. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar rektangelns nedre högra punkt. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar den högra övre rektangelpunkten. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Hämtar formens segment. |
| start_angle | float | r/w | Hämtar eller anger startvinkeln. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar den startande formpunkten. |
| sweep_angle | float | r/w | Hämtar eller anger svepvinkeln. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Hämtar objektets gränser. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Hämtar objektets gränser. |
| reverse() | Vänder ordningen på punkterna för denna form. |
| [transform(transform)](#transform_transform_3) | Tillämpar den angivna transformationen på formen. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Initierar en ny instans av klassen [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Initierar en ny instans av klassen [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Rektangeln. |
| start_angle | float | Startvinkeln. |
| sweep_angle | float | Svepvinkeln. |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Initierar en ny instans av klassen [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Rektangeln. |
| start_angle | float | Startvinkeln. |
| sweep_angle | float | Svepvinkeln. |
| is_closed | bool | Om den sätts till <c>true</c> är bågen sluten. Den slutna bågen degenererar i själva verket till en ellips. |

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

