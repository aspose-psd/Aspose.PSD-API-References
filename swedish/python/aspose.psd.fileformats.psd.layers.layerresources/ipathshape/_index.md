---
title: "IPathShape klass"
type: docs
weight: 380
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Hämtar eller anger egenskap som bestämmer om Shape är sluten. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Operationerna för att kombinera banformer (Booleska operationer). |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_items()](#get_items__1) | Hämtar en array av Bezier-knutar. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Tilldelar en array av Bexier-knutar. |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

Hämtar en array av Bezier-knutar.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array av BezierKnotRecord. |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Tilldelar en array av Bexier-knutar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array av bezier-knutar |

