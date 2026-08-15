---
title: "IPathShape Sınıfı"
type: docs
weight: 380
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Şeklin kapalı olup olmadığını belirleyen özelliği alır veya ayarlar. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Yol şekillerinin birleştirilmesi için işlemler (Boolean işlemler). |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_items()](#get_items__1) | Bezier düğümlerinin dizisini alır. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Bexier düğümlerinin dizisini atar. |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

Bezier düğümlerinin dizisini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | BezierKnotRecord dizisi. |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Bexier düğümlerinin dizisini atar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Bezier düğümlerinin dizisi |

