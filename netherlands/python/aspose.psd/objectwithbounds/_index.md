---
title: "ObjectWithBounds Klasse"
type: docs
weight: 3170
url: /nl/python-net/aspose.psd/objectwithbounds/
---

**Summary:** The object having bounds.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Haalt de grenzen van het object op. |
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

