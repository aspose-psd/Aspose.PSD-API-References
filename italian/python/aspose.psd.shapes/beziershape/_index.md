---
title: "Classe BezierShape"
type: docs
weight: 20
url: /it/python-net/aspose.psd.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | Inizializza una nuova istanza della classe [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/). |
| [BezierShape(points)](#BezierShape_points_2) | Inizializza una nuova istanza della classe [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/). |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | Inizializza una nuova istanza della classe [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Ottiene i limiti dell'oggetto. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il centro della forma. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto finale della forma. |
| has_segments | bool | r | Ottiene un valore che indica se la forma ha segmenti. |
| is_closed | bool | r/w | Ottiene o imposta un valore che indica se la forma è chiusa. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | Ottiene o imposta i punti della curva. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Ottiene i segmenti della forma. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ottiene il punto iniziale della forma. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Ottiene i limiti dell'oggetto. |
| reverse() | Inverte l'ordine dei punti per questa forma. |
| [transform(transform)](#transform_transform_3) | Applica la trasformazione specificata alla forma. |


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

Inizializza una nuova istanza della classe [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/).

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

Inizializza una nuova istanza della classe [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | L'array dei punti. |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

Inizializza una nuova istanza della classe [BezierShape](/psd/python-net/aspose.psd.shapes/beziershape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | L'array dei punti. |
| is_closed | bool | Se impostato su <c>true</c> la spline bezier è chiusa. |

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

