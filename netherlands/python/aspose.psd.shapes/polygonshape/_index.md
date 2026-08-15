---
title: "PolygonShape Klasse"
type: docs
weight: 60
url: /nl/python-net/aspose.psd.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Initialiseert een nieuw exemplaar van de [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) klasse. |
| [PolygonShape(points)](#PolygonShape_points_2) | Initialiseert een nieuw exemplaar van de [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) klasse. |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Initialiseert een nieuw exemplaar van de [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Haalt de grenzen van het object op. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het midden van de vorm op. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het eindpunt van de vorm op. |
| has_segments | bool | r | Haalt een waarde op die aangeeft of de vorm segmenten heeft. |
| is_closed | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of de vorm gesloten is. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | Haalt de krommingspunten op of stelt ze in. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Haalt de segmenten van de vorm op. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het startpunt van de vorm op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Haalt de grenzen van het object op. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Haalt de grenzen van het object op. |
| reverse() | Keert de volgorde van punten voor deze vorm om. |
| [transform(transform)](#transform_transform_3) | Past de opgegeven transformatie toe op de vorm. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Initialiseert een nieuw exemplaar van de [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) klasse.

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Initialiseert een nieuw exemplaar van de [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | De puntenarray. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Initialiseert een nieuw exemplaar van de [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | De puntenarray. |
| is_closed | bool | Als ingesteld op <c>true</c> is de veelhoek gesloten. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Haalt de grenzen van het object op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De matrix die moet worden toegepast voordat de grenzen worden berekend. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De geschatte grenzen van het object. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Haalt de grenzen van het object op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De matrix die moet worden toegepast voordat de grenzen worden berekend. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | De pen die voor het object wordt gebruikt. Dit kan de grootte van de objectgrenzen beïnvloeden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De geschatte grenzen van het object. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Past de opgegeven transformatie toe op de vorm.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | De toe te passen transformatie. |

