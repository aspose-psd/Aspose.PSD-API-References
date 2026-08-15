---
title: "Figure Sınıfı"
type: docs
weight: 1220
url: /tr/python-net/aspose.psd/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Figure

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Figure()](#Figure__1) | Figure sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Nesnenin sınırlarını alır veya ayarlar. |
| is_closed | bool | r/w | Bu şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. Kapalı bir şekil, yalnızca <br/>            ilk ve son şeklin şekilleri sürekli olduğunda fark yaratır. Bu durumda, ilk şeklin ilk noktası <br/>            son şeklin son noktasından düz bir çizgiyle bağlanır. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Tüm şekil segmentlerini alır. |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | r | Şeklin şekillerini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Şekle bir şekil ekler. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Şekle bir dizi şekil ekler. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Nesnenin sınırlarını alır. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Nesnenin sınırlarını alır. |
| [remove_shape(shape)](#remove_shape_shape_5) | Şekilden bir şekil kaldırır. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Şekilden bir dizi şekil kaldırır. |
| reverse() | Bu şeklin şekil sırasını ve şekil nokta sırasını tersine çevirir. |
| [transform(transform)](#transform_transform_7) | Belirtilen dönüşümü şekle uygular. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Figure sınıfının yeni bir örneğini başlatır

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Şekle bir şekil ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | Eklenecek şekil. |

### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Şekle bir dizi şekil ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Eklenecek şekiller. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

Nesnenin sınırlarını alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Sınırların öncesinde uygulanacak matris hesaplanacaktır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Tahmini nesne sınırları. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

Nesnenin sınırlarını alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Sınırların öncesinde uygulanacak matris hesaplanacaktır. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Nesne için kullanılacak kalem. Bu, nesnenin sınır boyutunu etkileyebilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Tahmini nesne sınırları. |


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Şekilden bir şekil kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shape | [Shape](/psd/python-net/aspose.psd/shape) | Kaldırılacak şekil. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Şekilden bir dizi şekil kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| shapes | [Shape[]](/psd/python-net/aspose.psd/shape) | Kaldırılacak şekil aralığı. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Belirtilen dönüşümü şekle uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Uygulanacak dönüşüm. |

