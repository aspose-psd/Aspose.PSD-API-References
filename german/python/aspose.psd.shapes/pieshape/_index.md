---
title: "PieShape Klasse"
type: docs
weight: 50
url: /de/python-net/aspose.psd.shapes/pieshape/
---

**Summary:** Represents a pie shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PieShape

**Inheritance:** EllipseShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PieShape()](#PieShape__1) | Initialisiert eine neue Instanz der [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/) Klasse. |
| [PieShape(rectangle, start_angle, sweep_angle)](#PieShape_rectangle_start_angle_sweep_angle_2) | Initialisiert eine neue Instanz der [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Liest die Begrenzungen des Objekts. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Liest das Zentrum der Form. |
| has_segments | bool | r | Liest einen Wert, der angibt, ob die Form Segmente hat. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Liest den linken unteren Rechteckpunkt. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Liest den linken oberen Rechteckpunkt. |
| rectangle_height | double | r | Liest die Rechteckhöhe. |
| rectangle_width | double | r | Liest die Rechteckbreite. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Liest den rechten unteren Rechteckpunkt. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Liest den rechten oberen Rechteckpunkt. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Liest die Segmente der Form. |
| start_angle | float | r/w | Liest oder setzt den Startwinkel. |
| sweep_angle | float | r/w | Liest oder setzt den Sweep-Winkel. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Liest die Begrenzungen des Objekts. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Liest die Begrenzungen des Objekts. |
| [transform(transform)](#transform_transform_3) | Wendet die angegebene Transformation auf die Form an. |


### Constructor: PieShape() {#PieShape__1}


```
 PieShape() 
```

Initialisiert eine neue Instanz der [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/) Klasse.

### Constructor: PieShape(rectangle, start_angle, sweep_angle) {#PieShape_rectangle_start_angle_sweep_angle_2}


```
 PieShape(rectangle, start_angle, sweep_angle) 
```

Initialisiert eine neue Instanz der [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Rechteck. |
| start_angle | float | Der Startwinkel. |
| sweep_angle | float | Der Sweep-Winkel. |

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

