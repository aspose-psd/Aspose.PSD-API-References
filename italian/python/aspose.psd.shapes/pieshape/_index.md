---
title: "Classe PieShape"
type: docs
weight: 50
url: /it/python-net/aspose.psd.shapes/pieshape/
---

**Summary:** Represents a pie shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PieShape

**Inheritance:** EllipseShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PieShape()](#PieShape__1) | Inizializza una nuova istanza della classe [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/). |
| [PieShape(rectangle, start_angle, sweep_angle)](#PieShape_rectangle_start_angle_sweep_angle_2) | Inizializza una nuova istanza della classe [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Ottiene i limiti dell'oggetto. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il centro della forma. |
| has_segments | bool | r | Ottiene un valore che indica se la forma ha segmenti. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto in basso a sinistra del rettangolo. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto in alto a sinistra del rettangolo. |
| rectangle_height | double | r | Ottiene l'altezza del rettangolo. |
| rectangle_width | double | r | Ottiene la larghezza del rettangolo. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto in basso a destra del rettangolo. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto in alto a destra del rettangolo. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Ottiene i segmenti della forma. |
| start_angle | float | r/w | Ottiene o imposta l'angolo di partenza. |
| sweep_angle | float | r/w | Ottiene o imposta l'angolo di sweep. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Ottiene i limiti dell'oggetto. |
| [transform(transform)](#transform_transform_3) | Applica la trasformazione specificata alla forma. |


### Constructor: PieShape() {#PieShape__1}


```
 PieShape() 
```

Inizializza una nuova istanza della classe [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/).

### Constructor: PieShape(rectangle, start_angle, sweep_angle) {#PieShape_rectangle_start_angle_sweep_angle_2}


```
 PieShape(rectangle, start_angle, sweep_angle) 
```

Inizializza una nuova istanza della classe [PieShape](/psd/python-net/aspose.psd.shapes/pieshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo. |
| start_angle | float | L'angolo di partenza. |
| sweep_angle | float | L'angolo di sweep. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Ottiene i limiti dell'oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice da applicare prima dei limiti sarà calcolata. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | I limiti stimati dell'oggetto. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Ottiene i limiti dell'oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice da applicare prima dei limiti sarà calcolata. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | La penna da usare per l'oggetto. Questo può influenzare la dimensione dei limiti dell'oggetto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | I limiti stimati dell'oggetto. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Applica la trasformazione specificata alla forma.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | La trasformazione da applicare. |

