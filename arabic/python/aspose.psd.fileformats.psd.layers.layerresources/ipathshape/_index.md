---
title: "فئة IPathShape"
type: docs
weight: 380
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | يحصل أو يعيّن الخاصية التي تحدد ما إذا كان Shape مغلقًا. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | العمليات لتجميع أشكال المسار (العمليات البوليانية). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_items()](#get_items__1) | يحصل على مصفوفة من عقد Bezier. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | يعيّن مصفوفة من عقد Bexier. |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

يحصل على مصفوفة من عقد Bezier.

**Returns**

| النوع | الوصف |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | مصفوفة من BezierKnotRecord. |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

يعيّن مصفوفة من عقد Bexier.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | مصفوفة من عقد بيزيه |

