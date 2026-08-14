---
title: "Classe Figure"
type: docs
weight: 1220
url: /it/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Figure()](#Figure__1) | Inizializza una nuova istanza della classe Figure |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Ottiene o imposta i limiti dell'oggetto. |
| is_closed | bool | r/w | Ottiene o imposta un valore che indica se questa figura è chiusa. Una figura chiusa farà differenza solo nel caso in cui<br/>            la prima e l'ultima forma della figura siano forme continue. In tal caso il primo punto della prima forma sarà<br/>            collegato da una linea retta all'ultimo punto dell'ultima forma. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Ottiene tutti i segmenti della figura. |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | Ottiene le forme della figura. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Aggiunge una forma alla figura. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Aggiunge un intervallo di forme alla figura. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Ottiene i limiti dell'oggetto. |
| [remove_shape(shape)](#remove_shape_shape_5) | Rimuove una forma dalla figura. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Rimuove un intervallo di forme dalla figura. |
| reverse() | Inverte l'ordine delle forme di questa figura e l'ordine dei punti delle forme. |
| [transform(transform)](#transform_transform_7) | Applica la trasformazione specificata alla forma. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Inizializza una nuova istanza della classe Figure

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Aggiunge una forma alla figura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | La forma da aggiungere. |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Aggiunge un intervallo di forme alla figura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Le forme da aggiungere. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Rimuove una forma dalla figura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | La forma da rimuovere. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Rimuove un intervallo di forme dalla figura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | L'intervallo di forme da rimuovere. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Applica la trasformazione specificata alla forma.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | La trasformazione da applicare. |

