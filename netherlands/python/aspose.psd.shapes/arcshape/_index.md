---
title: "ArcShape Klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.psd.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Initialiseert een nieuw exemplaar van de [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) klasse. |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Initialiseert een nieuw exemplaar van de [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) klasse. |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Initialiseert een nieuw exemplaar van de [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Haalt de grenzen van het object op. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het midden van de vorm op. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het eindpunt van de vorm op. |
| has_segments | bool | r | Haalt een waarde op die aangeeft of de vorm segmenten heeft. |
| is_closed | bool | r/w | Haalt of stelt een waarde in die aangeeft of de geordende vorm gesloten is. Bij het verwerken van een gesloten geordende vorm hebben de start- en eindpunten geen betekenis. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het linksonderhoekpunt van de rechthoek op. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het linkerbovenhoekpunt van de rechthoek op. |
| rectangle_height | double | r | Haalt de hoogte van de rechthoek op. |
| rectangle_width | double | r | Haalt de breedte van de rechthoek op. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het rechtsonderhoekpunt van de rechthoek op. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het rechterbovenhoekpunt van de rechthoek op. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Haalt de segmenten van de vorm op. |
| start_angle | float | r/w | Haalt of stelt de starthoek in. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Haalt het startpunt van de vorm op. |
| sweep_angle | float | r/w | Haalt of stelt de sweephoek in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Haalt de grenzen van het object op. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Haalt de grenzen van het object op. |
| reverse() | Keert de volgorde van punten voor deze vorm om. |
| [transform(transform)](#transform_transform_3) | Past de opgegeven transformatie toe op de vorm. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Initialiseert een nieuw exemplaar van de [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) klasse.

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Initialiseert een nieuw exemplaar van de [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De rechthoek. |
| start_angle | float | De starthoek. |
| sweep_angle | float | De sweephoek. |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Initialiseert een nieuw exemplaar van de [ArcShape](/psd/python-net/aspose.psd.shapes/arcshape/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De rechthoek. |
| start_angle | float | De starthoek. |
| sweep_angle | float | De sweephoek. |
| is_closed | bool | Indien ingesteld op <c>true</c> is de boog gesloten. De gesloten boog degradeert eigenlijk tot een ellips. |

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

