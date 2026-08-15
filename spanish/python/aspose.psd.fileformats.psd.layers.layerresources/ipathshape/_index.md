---
title: "Clase IPathShape"
type: docs
weight: 380
url: /es/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Obtiene o establece la propiedad que determina si Shape está cerrada. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Las operaciones para combinar las formas de ruta (operaciones booleanas). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_items()](#get_items__1) | Obtiene una matriz de nudos Bezier. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Asigna una matriz de nudos Bexier. |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

Obtiene una matriz de nudos Bezier.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Matriz de BezierKnotRecord. |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Asigna una matriz de nudos Bexier.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Matriz de nudos Bézier |

