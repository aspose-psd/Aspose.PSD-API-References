---
title: "Classe ArcShape"
type: docs
weight: 10
url: /it/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Inizializza una nuova istanza della classe [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Inizializza una nuova istanza della classe [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Inizializza una nuova istanza della classe [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Ottiene i limiti dell'oggetto. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il centro della forma. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto finale della forma. |
| has_segments | bool | r | Ottiene un valore che indica se la forma ha segmenti. |
| is_closed | bool | r/w | Ottiene o imposta un valore che indica se la forma ordinata è chiusa. Quando si elabora una forma ordinata chiusa, i punti di inizio e fine non hanno significato. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto in basso a sinistra del rettangolo. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto in alto a sinistra del rettangolo. |
| rectangle_height | double | r | Ottiene l'altezza del rettangolo. |
| rectangle_width | double | r | Ottiene la larghezza del rettangolo. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto in basso a destra del rettangolo. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto in alto a destra del rettangolo. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Ottiene i segmenti della forma. |
| start_angle | float | r/w | Ottiene o imposta l'angolo di partenza. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto iniziale della forma. |
| sweep_angle | float | r/w | Ottiene o imposta l'angolo di sweep. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Ottiene i limiti dell'oggetto. |
| reverse() | Inverte l'ordine dei punti per questa forma. |
| [transform(transform)](#transform_transform_3) | Applica la trasformazione specificata alla forma. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Inizializza una nuova istanza della classe [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Inizializza una nuova istanza della classe [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo. |
| start_angle | float | L'angolo di partenza. |
| sweep_angle | float | L'angolo di sweep. |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Inizializza una nuova istanza della classe [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Il rettangolo. |
| start_angle | float | L'angolo di partenza. |
| sweep_angle | float | L'angolo di sweep. |
| is_closed | bool | Se impostato su <c>true</c> l'arco è chiuso. L'arco chiuso in realtà si degenere in un'ellisse. |

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

