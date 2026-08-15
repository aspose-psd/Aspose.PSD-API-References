---
title: "PolygonShape-klass"
type: docs
weight: 60
url: /sv/python-net/aspose.psd.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Initierar en ny instans av klassen [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
| [PolygonShape(points)](#PolygonShape_points_2) | Initierar en ny instans av klassen [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Initierar en ny instans av klassen [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Hämtar objektets gränser. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar formens centrum. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar den avslutande formpunkten. |
| has_segments | bool | r | Hämtar ett värde som indikerar om formen har segment. |
| is_closed | bool | r/w | Hämtar eller anger ett värde som indikerar om formen är sluten. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | Hämtar eller anger kurvpunkterna. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Hämtar formens segment. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Hämtar den startande formpunkten. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Hämtar objektets gränser. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Hämtar objektets gränser. |
| reverse() | Vänder ordningen på punkterna för denna form. |
| [transform(transform)](#transform_transform_3) | Tillämpar den angivna transformationen på formen. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Initierar en ny instans av klassen [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Initierar en ny instans av klassen [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Punktarrayen. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Initierar en ny instans av klassen [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Punktarrayen. |
| is_closed | bool | Om den är satt till <c>true</c> är polygonen sluten. |

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

