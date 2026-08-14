---
title: "ArcShape Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Initialisiert eine neue Instanz der [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) Klasse. |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Initialisiert eine neue Instanz der [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) Klasse. |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Initialisiert eine neue Instanz der [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Liest die Begrenzungen des Objekts. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Liest das Zentrum der Form. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ruft den Endpunkt der Form ab. |
| has_segments | bool | r | Liest einen Wert, der angibt, ob die Form Segmente hat. |
| is_closed | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die geordnete Form geschlossen ist. Beim Verarbeiten einer geschlossenen geordneten Form haben die Start- und Endpunkte keine Bedeutung. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Liest den linken unteren Rechteckpunkt. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Liest den linken oberen Rechteckpunkt. |
| rectangle_height | double | r | Liest die Rechteckhöhe. |
| rectangle_width | double | r | Liest die Rechteckbreite. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Liest den rechten unteren Rechteckpunkt. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Liest den rechten oberen Rechteckpunkt. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Liest die Segmente der Form. |
| start_angle | float | r/w | Liest oder setzt den Startwinkel. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ruft den Startpunkt der Form ab. |
| sweep_angle | float | r/w | Liest oder setzt den Sweep-Winkel. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Liest die Begrenzungen des Objekts. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Liest die Begrenzungen des Objekts. |
| reverse() | Kehrt die Reihenfolge der Punkte für diese Form um. |
| [transform(transform)](#transform_transform_3) | Wendet die angegebene Transformation auf die Form an. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Initialisiert eine neue Instanz der [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) Klasse.

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Initialisiert eine neue Instanz der [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Rechteck. |
| start_angle | float | Der Startwinkel. |
| sweep_angle | float | Der Sweep-Winkel. |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Initialisiert eine neue Instanz der [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Rechteck. |
| start_angle | float | Der Startwinkel. |
| sweep_angle | float | Der Sweep-Winkel. |
| is_closed | bool | Wenn auf <c>true</c> gesetzt, ist der Bogen geschlossen. Der geschlossene Bogen degeneriert tatsächlich zu einer Ellipse. |

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

