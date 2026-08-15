---
title: "Figure‑klass"
type: docs
weight: 1220
url: /sv/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Figure()](#Figure__1) | Initierar en ny instans av Figure‑klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Hämtar eller anger objektets gränser. |
| is_closed | bool | r/w | Hämtar eller anger ett värde som indikerar om denna figur är sluten. En sluten figur gör endast skillnad i fall där<br/>            den första och den sista figurens former är kontinuerliga former. I sådant fall kommer den första punkten i den första formen att vara<br/>            ansluten med en rak linje från den sista punkten i den sista formen. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Hämtar hela figursegmenten. |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | Hämtar figurens former. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Lägger till en form i figuren. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Lägger till ett intervall av former i figuren. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Hämtar objektets gränser. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Hämtar objektets gränser. |
| [remove_shape(shape)](#remove_shape_shape_5) | Tar bort en form från figuren. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Tar bort ett intervall av former från figuren. |
| reverse() | Vänder ordningen på figurens former och formernas punktordning. |
| [transform(transform)](#transform_transform_7) | Tillämpar den angivna transformationen på formen. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Initierar en ny instans av Figure‑klassen

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Lägger till en form i figuren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | Formen att lägga till. |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Lägger till ett intervall av former i figuren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Formerna att lägga till. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriserna som ska tillämpas innan gränser beräknas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Det uppskattade objektets gränser. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriserna som ska tillämpas innan gränser beräknas. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Pennan som ska användas för objektet. Detta kan påverka objektets gränsstorlek. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Det uppskattade objektets gränser. |


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Tar bort en form från figuren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | Formen att ta bort. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Tar bort ett intervall av former från figuren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Intervallet av former att ta bort. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Tillämpar den angivna transformationen på formen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Transformationen att tillämpa. |

