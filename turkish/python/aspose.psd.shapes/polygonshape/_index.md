---
title: "PolygonShape Sınıfı"
type: docs
weight: 60
url: /tr/python-net/aspose.psd.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Yeni bir [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) sınıfı örneği başlatır. |
| [PolygonShape(points)](#PolygonShape_points_2) | Yeni bir [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) sınıfı örneği başlatır. |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Yeni bir [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Nesnenin sınırlarını alır. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Şeklin merkezini alır. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Şeklin bitiş noktasını alır. |
| has_segments | bool | r | Şeklin segmentlere sahip olup olmadığını gösteren bir değeri alır. |
| is_closed | bool | r/w | Şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | Eğri noktalarını alır veya ayarlar. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Şekil segmentlerini alır. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Şeklin başlangıç noktasını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Nesnenin sınırlarını alır. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Nesnenin sınırlarını alır. |
| reverse() | Bu şekil için nokta sırasını tersine çevirir. |
| [transform(transform)](#transform_transform_3) | Belirtilen dönüşümü şekle uygular. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Yeni bir [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) sınıfı örneği başlatır.

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Yeni bir [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Nokta dizisi. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Yeni bir [PolygonShape](/psd/python-net/aspose.psd.shapes/polygonshape/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Nokta dizisi. |
| is_closed | bool | Eğer <c>true</c> olarak ayarlanırsa çokgen kapalıdır. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Belirtilen dönüşümü şekle uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Uygulanacak dönüşüm. |

