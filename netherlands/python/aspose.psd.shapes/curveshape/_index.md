---
title: "CurveShape Klasse"
type: docs
weight: 30
url: /nl/python-net/aspose.psd.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Initialiseert een nieuw exemplaar van de [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) klasse. |
| [CurveShape(points)](#CurveShape_points_2) | Initialiseert een nieuw exemplaar van de [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) klasse. De standaard spanning van 0,5 wordt gebruikt. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Initialiseert een nieuw exemplaar van de [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) klasse. De standaard spanning van 0,5 wordt gebruikt. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Initialiseert een nieuw exemplaar van de [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) klasse. |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Initialiseert een nieuw exemplaar van de [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) klasse. |
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
| spanning | float | r/w | Haalt of stelt de curve-spanning in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Haalt de grenzen van het object op. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Haalt de grenzen van het object op. |
| reverse() | Keert de volgorde van punten voor deze vorm om. |
| [transform(transform)](#transform_transform_3) | Past de opgegeven transformatie toe op de vorm. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Initialiseert een nieuw exemplaar van de [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) klasse.

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Initialiseert een nieuw exemplaar van de [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) klasse. De standaard spanning van 0,5 wordt gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | De puntenarray. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Initialiseert een nieuw exemplaar van de [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) klasse. De standaard spanning van 0,5 wordt gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | De puntenarray. |
| is_closed | bool | Als ingesteld op <c>true</c> is de curve gesloten. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Initialiseert een nieuw exemplaar van de [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | De puntenarray. |
| spanning | float | De curve-spanning. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Initialiseert een nieuw exemplaar van de [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | De puntenarray. |
| spanning | float | De curve-spanning. |
| is_closed | bool | Als ingesteld op <c>true</c> is de curve gesloten. |

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

