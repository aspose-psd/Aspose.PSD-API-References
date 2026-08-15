---
title: "Figure Klasse"
type: docs
weight: 1220
url: /nl/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Figure()](#Figure__1) | Initialiseert een nieuw exemplaar van de Figure-klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Haalt de grenzen van het object op of stelt ze in. |
| is_closed | bool | r/w | Haalt een waarde op of stelt een waarde in die aangeeft of deze figuur gesloten is. Een gesloten figuur maakt alleen een verschil in het geval waar<br/>            de eerste en de laatste vormen van de figuur doorlopende vormen zijn. In dat geval wordt het eerste punt van de eerste vorm<br/>            verbonden met een rechte lijn vanaf het laatste punt van de laatste vorm. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Haalt de volledige segmenten van de figuur op. |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | Haalt de vormen van de figuur op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Voegt een vorm toe aan de figuur. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Voegt een reeks vormen toe aan de figuur. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Haalt de grenzen van het object op. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Haalt de grenzen van het object op. |
| [remove_shape(shape)](#remove_shape_shape_5) | Verwijdert een vorm uit de figuur. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Verwijdert een reeks vormen uit de figuur. |
| reverse() | Keert de volgorde van de vormen en de volgorde van de vormpunten in deze figuur om. |
| [transform(transform)](#transform_transform_7) | Past de opgegeven transformatie toe op de vorm. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Initialiseert een nieuw exemplaar van de Figure-klasse

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Voegt een vorm toe aan de figuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | De toe te voegen vorm. |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Voegt een reeks vormen toe aan de figuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | De toe te voegen vormen. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

Haalt de grenzen van het object op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De matrix die moet worden toegepast voordat de grenzen worden berekend. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De geschatte grenzen van het object. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

Haalt de grenzen van het object op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | De matrix die moet worden toegepast voordat de grenzen worden berekend. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | De pen die voor het object wordt gebruikt. Dit kan de grootte van de objectgrenzen beïnvloeden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De geschatte grenzen van het object. |


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Verwijdert een vorm uit de figuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | De te verwijderen vorm. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Verwijdert een reeks vormen uit de figuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Het bereik van te verwijderen vormen. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Past de opgegeven transformatie toe op de vorm.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | De toe te passen transformatie. |

