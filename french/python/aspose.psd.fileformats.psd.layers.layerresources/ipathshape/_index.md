---
title: "Classe IPathShape"
type: docs
weight: 380
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Obtient ou définit la propriété qui détermine si la forme est fermée. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Les opérations de combinaison des formes de chemin (opérations booléennes). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_items()](#get_items__1) | Obtient le tableau de nœuds de Bézier. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Assigne un tableau de nœuds Bexier. |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

Obtient le tableau de nœuds de Bézier.

**Returns**

| Type | Description |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Tableau de BezierKnotRecord. |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Assigne un tableau de nœuds Bexier.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Tableau de nœuds Bézier |

