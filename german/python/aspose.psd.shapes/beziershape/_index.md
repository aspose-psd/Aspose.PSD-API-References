---
title: "BezierShape Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.psd.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | Initialisiert eine neue Instanz der [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) Klasse. |
| [BezierShape(points)](#BezierShape_points_2) | Initialisiert eine neue Instanz der [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) Klasse. |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | Initialisiert eine neue Instanz der [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) Klasse. |
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


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

Initialisiert eine neue Instanz der [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) Klasse.

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

Initialisiert eine neue Instanz der [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Das Punkte-Array. |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

Initialisiert eine neue Instanz der [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Das Punkte-Array. |
| is_closed | bool | Wenn auf <c>true</c> gesetzt, ist die Bezier-Spline geschlossen. |

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

