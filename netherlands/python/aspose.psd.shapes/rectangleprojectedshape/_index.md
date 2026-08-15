---
title: "RectangleProjectedShape Klasse"
type: docs
weight: 70
url: /nl/python-net/aspose.psd.shapes/rectangleprojectedshape/
---

**Summary:** Represents a shape which is projected over rectangle turned to a particular orientation.<br/>            Specified by four points which can be rotated in space maintaining the same edges length and 90 degrees between adjacent edges.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.RectangleProjectedShape

**Inheritance:** Shape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Haalt de grenzen van het object op. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het midden van de vorm op. |
| has_segments | bool | r | Haalt een waarde op die aangeeft of de vorm segmenten heeft. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het linksonderhoekpunt van de rechthoek op. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het linkerbovenhoekpunt van de rechthoek op. |
| rectangle_height | double | r | Haalt de hoogte van de rechthoek op. |
| rectangle_width | double | r | Haalt de breedte van de rechthoek op. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het rechtsonderhoekpunt van de rechthoek op. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het rechterbovenhoekpunt van de rechthoek op. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Haalt de segmenten van de vorm op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Haalt de grenzen van het object op. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Haalt de grenzen van het object op. |
| [transform(transform)](#transform_transform_3) | Past de opgegeven transformatie toe op de vorm. |


### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Past de opgegeven transformatie toe op de vorm.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | De toe te passen transformatie. |

