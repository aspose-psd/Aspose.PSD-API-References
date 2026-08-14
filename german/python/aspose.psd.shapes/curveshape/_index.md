---
title: "CurveShape Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.psd.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Initialisiert eine neue Instanz der Klasse [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | Initialisiert eine neue Instanz der Klasse [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Die Standard-Spannung von 0,5 wird verwendet. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Initialisiert eine neue Instanz der Klasse [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Die Standard-Spannung von 0,5 wird verwendet. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Initialisiert eine neue Instanz der Klasse [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Initialisiert eine neue Instanz der Klasse [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
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
| Spannung | float | r/w | Ruft die Kurvenspannung ab oder legt sie fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Liest die Begrenzungen des Objekts. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Liest die Begrenzungen des Objekts. |
| reverse() | Kehrt die Reihenfolge der Punkte für diese Form um. |
| [transform(transform)](#transform_transform_3) | Wendet die angegebene Transformation auf die Form an. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Initialisiert eine neue Instanz der Klasse [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Initialisiert eine neue Instanz der Klasse [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Die Standard-Spannung von 0,5 wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Das Punkte-Array. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Initialisiert eine neue Instanz der Klasse [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Die Standard-Spannung von 0,5 wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Das Punkte-Array. |
| is_closed | bool | Wenn auf <c>true</c> gesetzt, ist die Kurve geschlossen. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Initialisiert eine neue Instanz der Klasse [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Das Punkte-Array. |
| Spannung | float | Die Kurvenspannung. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Initialisiert eine neue Instanz der Klasse [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Das Punkte-Array. |
| Spannung | float | Die Kurvenspannung. |
| is_closed | bool | Wenn auf <c>true</c> gesetzt, ist die Kurve geschlossen. |

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

