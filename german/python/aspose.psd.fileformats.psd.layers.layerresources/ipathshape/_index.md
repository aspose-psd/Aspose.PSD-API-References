---
title: "IPathShape Klasse"
type: docs
weight: 380
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Liest oder setzt die Eigenschaft, die bestimmt, ob die Form geschlossen ist. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Die Vorgänge zum Kombinieren von Pfadformen (Boolesche Operationen). |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_items()](#get_items__1) | Liest ein Array von Bézier-Knoten. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Weist ein Array von Bexier-Knoten zu. |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

Liest ein Array von Bézier-Knoten.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array von BezierKnotRecord. |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Weist ein Array von Bexier-Knoten zu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array von Bezier-Knoten |

