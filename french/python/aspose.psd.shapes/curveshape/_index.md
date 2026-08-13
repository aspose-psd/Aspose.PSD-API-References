---
title: "Classe CurveShape"
type: docs
weight: 30
url: /fr/python-net/aspose.psd.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Initialise une nouvelle instance de la classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | Initialise une nouvelle instance de la classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). La tension par défaut de 0,5 est utilisée. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Initialise une nouvelle instance de la classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). La tension par défaut de 0,5 est utilisée. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Initialise une nouvelle instance de la classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Initialise une nouvelle instance de la classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtient les limites de l'objet. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le centre de la forme. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point final de la forme. |
| has_segments | bool | r | Obtient une valeur indiquant si la forme possède des segments. |
| is_closed | bool | r/w | Obtient ou définit une valeur indiquant si la forme est fermée. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | Obtient ou définit les points de la courbe. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Obtient les segments de la forme. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point de départ de la forme. |
| tension | float | r/w | Obtient ou définit la tension de la courbe. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtient les limites de l'objet. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtient les limites de l'objet. |
| reverse() | Inverse l'ordre des points pour cette forme. |
| [transform(transform)](#transform_transform_3) | Applique la transformation spécifiée à la forme. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Initialise une nouvelle instance de la classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Initialise une nouvelle instance de la classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). La tension par défaut de 0,5 est utilisée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Le tableau de points. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Initialise une nouvelle instance de la classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). La tension par défaut de 0,5 est utilisée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Le tableau de points. |
| is_closed | bool | si défini sur <c>true</c> la courbe est fermée. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Initialise une nouvelle instance de la classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Le tableau de points. |
| tension | float | La tension de la courbe. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Initialise une nouvelle instance de la classe [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Le tableau de points. |
| tension | float | La tension de la courbe. |
| is_closed | bool | si défini sur <c>true</c> la courbe est fermée. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Obtient les limites de l'objet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice à appliquer avant le calcul des limites sera calculée. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Les limites estimées de l'objet. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Obtient les limites de l'objet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | La matrice à appliquer avant le calcul des limites sera calculée. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Le crayon à utiliser pour l'objet. Cela peut influencer la taille des limites de l'objet. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Les limites estimées de l'objet. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Applique la transformation spécifiée à la forme.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | La transformation à appliquer. |

