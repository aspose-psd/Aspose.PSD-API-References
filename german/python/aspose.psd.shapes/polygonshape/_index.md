---
title: "PolygonShape Klasse"
type: docs
weight: 60
url: /de/python-net/aspose.psd.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Initialisiert eine neue Instanz der Klasse [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
| [PolygonShape(points)](#PolygonShape_points_2) | Initialisiert eine neue Instanz der Klasse [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Initialisiert eine neue Instanz der Klasse [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Liest die Begrenzungen des Objekts. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Liest das Zentrum der Form. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ruft den Endpunkt der Form ab. |
| has_segments | bool | r | Liest einen Wert, der angibt, ob die Form Segmente hat. |
| is_closed | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Form geschlossen ist. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | Ruft die Kurvenpunkte ab oder legt sie fest. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Liest die Segmente der Form. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ruft den Startpunkt der Form ab. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Liest die Begrenzungen des Objekts. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Liest die Begrenzungen des Objekts. |
| reverse() | Kehrt die Reihenfolge der Punkte für diese Form um. |
| [transform(transform)](#transform_transform_3) | Wendet die angegebene Transformation auf die Form an. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Initialisiert eine neue Instanz der Klasse [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Initialisiert eine neue Instanz der Klasse [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Das Punkte-Array. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Initialisiert eine neue Instanz der Klasse [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Das Punkte-Array. |
| is_closed | bool | Wenn auf <c>true</c> gesetzt, ist das Polygon geschlossen. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Liest die Begrenzungen des Objekts.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Die Matrix, die vor der Begrenzung angewendet wird, wird berechnet. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Die geschätzten Begrenzungen des Objekts. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Liest die Begrenzungen des Objekts.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Die Matrix, die vor der Begrenzung angewendet wird, wird berechnet. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Der Stift, der für das Objekt verwendet wird. Dies kann die Größe der Objektbegrenzungen beeinflussen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Die geschätzten Begrenzungen des Objekts. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Wendet die angegebene Transformation auf die Form an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Die anzuwendende Transformation. |

