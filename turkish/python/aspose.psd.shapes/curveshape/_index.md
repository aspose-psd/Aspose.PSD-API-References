---
title: "CurveShape Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.psd.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Yeni bir [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) sınıfı örneği başlatır. |
| [CurveShape(points)](#CurveShape_points_2) | Yeni bir [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) sınıfı örneği başlatır. Varsayılan 0.5 gerilim kullanılır. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Yeni bir [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) sınıfı örneği başlatır. Varsayılan 0.5 gerilim kullanılır. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Yeni bir [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) sınıfı örneği başlatır. |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Yeni bir [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) sınıfı örneği başlatır. |
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
| gerilim | float | r/w | Eğri gerilimini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Nesnenin sınırlarını alır. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Nesnenin sınırlarını alır. |
| reverse() | Bu şekil için nokta sırasını tersine çevirir. |
| [transform(transform)](#transform_transform_3) | Belirtilen dönüşümü şekle uygular. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Yeni bir [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) sınıfı örneği başlatır.

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Yeni bir [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) sınıfı örneği başlatır. Varsayılan 0.5 gerilim kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Nokta dizisi. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Yeni bir [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) sınıfı örneği başlatır. Varsayılan 0.5 gerilim kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Nokta dizisi. |
| is_closed | bool | Eğer <c>true</c> olarak ayarlanırsa eğri kapalıdır. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Yeni bir [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Nokta dizisi. |
| gerilim | float | Eğri gerilimi. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Yeni bir [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Nokta dizisi. |
| gerilim | float | Eğri gerilimi. |
| is_closed | bool | Eğer <c>true</c> olarak ayarlanırsa eğri kapalıdır. |

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

