---
title: IPathShape Class
type: docs
weight: 340
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 23.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Gets or sets property that determines if Shape is closed. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | The operations for the path shapes combining (Boolean operations). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_items()](#get_items__1) | Gets array of Bezier knots. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Assignes array of Bexier knots. |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

Gets array of Bezier knots.

**Returns**

| Type | Description |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array of BezierKnotRecord. |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Assignes array of Bexier knots.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array of bezier knots |

