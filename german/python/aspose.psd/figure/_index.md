---
title: "Figure-Klasse"
type: docs
weight: 1220
url: /de/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Figure()](#Figure__1) | Initialisiert eine neue Instanz der Figure-Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Liest oder setzt die Grenzen des Objekts. |
| is_closed | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Figur geschlossen ist. Eine geschlossene Figur macht nur einen Unterschied, wenn<br/>            die erste und die letzte Form der Figur kontinuierliche Formen sind. In einem solchen Fall wird der erste Punkt der ersten Form<br/>            durch eine gerade Linie mit dem letzten Punkt der letzten Form verbunden. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Liest die gesamten Figursegmente. |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | Liest die Figurformen. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Fügt der Figur eine Form hinzu. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Fügt der Figur einen Bereich von Formen hinzu. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Liest die Begrenzungen des Objekts. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Liest die Begrenzungen des Objekts. |
| [remove_shape(shape)](#remove_shape_shape_5) | Entfernt eine Form aus der Figur. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Entfernt einen Bereich von Formen aus der Figur. |
| reverse() | Kehrt die Reihenfolge der Formen dieser Figur und die Punktreihenfolge der Formen um. |
| [transform(transform)](#transform_transform_7) | Wendet die angegebene Transformation auf die Form an. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Initialisiert eine neue Instanz der Figure-Klasse

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Fügt der Figur eine Form hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | Die hinzuzufügende Form. |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Fügt der Figur einen Bereich von Formen hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Die hinzuzufügenden Formen. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Entfernt eine Form aus der Figur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | Die zu entfernende Form. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Entfernt einen Bereich von Formen aus der Figur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Der zu entfernende Formenbereich. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Wendet die angegebene Transformation auf die Form an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Die anzuwendende Transformation. |

