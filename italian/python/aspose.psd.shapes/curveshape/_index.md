---
title: "Classe CurveShape"
type: docs
weight: 30
url: /it/python-net/aspose.psd.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Inizializza una nuova istanza della classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | Inizializza una nuova istanza della classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Viene utilizzata la tensione predefinita di 0.5. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Inizializza una nuova istanza della classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Viene utilizzata la tensione predefinita di 0.5. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Inizializza una nuova istanza della classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Inizializza una nuova istanza della classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
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
| tensione | float | r/w | Ottiene o imposta la tensione della curva. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Ottiene i limiti dell'oggetto. |
| reverse() | Inverte l'ordine dei punti per questa forma. |
| [transform(transform)](#transform_transform_3) | Applica la trasformazione specificata alla forma. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Inizializza una nuova istanza della classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Inizializza una nuova istanza della classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Viene utilizzata la tensione predefinita di 0.5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | L'array dei punti. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Inizializza una nuova istanza della classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Viene utilizzata la tensione predefinita di 0.5.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | L'array dei punti. |
| is_closed | bool | Se impostato su <c>true</c> la curva è chiusa. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Inizializza una nuova istanza della classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | L'array dei punti. |
| tensione | float | La tensione della curva. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Inizializza una nuova istanza della classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | L'array dei punti. |
| tensione | float | La tensione della curva. |
| is_closed | bool | Se impostato su <c>true</c> la curva è chiusa. |

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

