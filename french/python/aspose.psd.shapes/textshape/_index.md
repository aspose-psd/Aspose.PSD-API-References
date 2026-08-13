---
title: "Classe TextShape"
type: docs
weight: 90
url: /fr/python-net/aspose.psd.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextShape()](#TextShape__1) | Initialise une nouvelle instance de la classe [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Initialise une nouvelle instance de la classe [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Obtient les limites de l'objet. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le centre de la forme. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r/w | Obtient ou définit la police utilisée pour dessiner le texte. |
| has_segments | bool | r | Obtient une valeur indiquant si la forme possède des segments. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point inférieur gauche du rectangle. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point supérieur gauche du rectangle. |
| rectangle_height | double | r | Obtient la hauteur du rectangle. |
| rectangle_width | double | r | Obtient la largeur du rectangle. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point inférieur droit du rectangle. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Obtient le point supérieur droit du rectangle. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Obtient les segments de la forme. |
| text | chaîne | r/w | Obtient ou définit le texte dessiné. |
| text_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r/w | Obtient ou définit le format du texte. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtient les limites de l'objet. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtient les limites de l'objet. |
| [transform(transform)](#transform_transform_3) | Applique la transformation spécifiée à la forme. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Initialise une nouvelle instance de la classe [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Initialise une nouvelle instance de la classe [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| text | chaîne | Le texte à dessiner. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Le rectangle du texte. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | La police à utiliser. |
| string_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | Le format de chaîne. |

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

