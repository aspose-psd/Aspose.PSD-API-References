---
title: "Kelas PathShape"
type: docs
weight: 750
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [PathShape()](#PathShape__1) | Menginisialisasi sebuah instance baru dari kelas [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | Menginisialisasi sebuah instance baru dari kelas [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini tertutup. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Mendapatkan atau mengatur operasi jalur (operasi Boolean). |
| shape_index | ushort | r/w | Mendapatkan atau mengatur indeks bentuk jalur saat ini dalam lapisan. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_items()](#get_items__1) | Mendapatkan array simpul Bezier. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Menetapkan array simpul Bezier. |
| [to_vector_path_records()](#to_vector_path_records__3) | Membuat catatan [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) berdasarkan instance ini. |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

Menginisialisasi sebuah instance baru dari kelas [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

Menginisialisasi sebuah instance baru dari kelas [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | Catatan panjang. |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Catatan simpul bezier. |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Mendapatkan array simpul Bezier.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array dari BezierKnotRecord |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Menetapkan array simpul Bezier.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array simpul bezier |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

Membuat catatan [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) berdasarkan instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | Mengembalikan satu [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) dan [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) untuk setiap titik dalam instance ini. |


