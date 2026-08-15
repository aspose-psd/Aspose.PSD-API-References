---
title: "ArcShape Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Yeni bir [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) sınıfı örneği başlatır. |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Yeni bir [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) sınıfı örneği başlatır. |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Yeni bir [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Nesnenin sınırlarını alır. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Şeklin merkezini alır. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Şeklin bitiş noktasını alır. |
| has_segments | bool | r | Şeklin segmentlere sahip olup olmadığını gösteren bir değeri alır. |
| is_closed | bool | r/w | Siparişli şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. Kapalı siparişli şekil işlenirken başlangıç ve bitiş noktaları bir anlam taşımaz. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Sol alt dikdörtgen noktasını alır. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Sol üst dikdörtgen noktasını alır. |
| rectangle_height | double | r | Dikdörtgen yüksekliğini alır. |
| rectangle_width | double | r | Dikdörtgen genişliğini alır. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Sağ alt dikdörtgen noktasını alır. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Sağ üst dikdörtgen noktasını alır. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Şekil segmentlerini alır. |
| start_angle | float | r/w | Başlangıç açısını alır veya ayarlar. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Şeklin başlangıç noktasını alır. |
| sweep_angle | float | r/w | Tarama açısını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Nesnenin sınırlarını alır. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Nesnenin sınırlarını alır. |
| reverse() | Bu şekil için nokta sırasını tersine çevirir. |
| [transform(transform)](#transform_transform_3) | Belirtilen dönüşümü şekle uygular. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Yeni bir [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) sınıfı örneği başlatır.

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Yeni bir [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Dikdörtgen. |
| start_angle | float | Başlangıç açısı. |
| sweep_angle | float | Tarama açısı. |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Yeni bir [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Dikdörtgen. |
| start_angle | float | Başlangıç açısı. |
| sweep_angle | float | Tarama açısı. |
| is_closed | bool | Eğer <c>true</c> olarak ayarlanırsa yay kapatılır. Kapalı yay aslında bir elipse dönüşür. |

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

