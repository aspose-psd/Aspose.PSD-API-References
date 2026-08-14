---
title: "Kelas IPathShape"
type: docs
weight: 380
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Mendapatkan atau mengatur properti yang menentukan apakah Shape tertutup. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Operasi untuk menggabungkan bentuk jalur (operasi Boolean). |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_items()](#get_items__1) | Mendapatkan array simpul Bezier. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Menetapkan array dari simpul Bexier. |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

Mendapatkan array simpul Bezier.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array dari BezierKnotRecord. |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Menetapkan array dari simpul Bexier.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array simpul bezier |

