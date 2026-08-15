---
title: "PathShape Sınıfı"
type: docs
weight: 750
url: /tr/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PathShape()](#PathShape__1) | Yeni bir [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) sınıfının örneğini başlatır. |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | Yeni bir [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Bu örneğin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Yol işlemlerini (Boolean işlemler) alır veya ayarlar. |
| shape_index | ushort | r/w | Katmandaki geçerli yol şeklinin dizinini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_items()](#get_items__1) | Bezier düğümlerinin dizisini alır. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Bezier düğümlerinin dizisini atar. |
| [to_vector_path_records()](#to_vector_path_records__3) | Bu örnek temelinde [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) kayıtlarını oluşturur. |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

Yeni bir [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) sınıfının örneğini başlatır.

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

Yeni bir [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) sınıfının örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | Uzunluk kaydı. |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Bezier düğüm kayıtları. |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Bezier düğümlerinin dizisini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | BezierKnotRecord dizisi |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Bezier düğümlerinin dizisini atar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Bezier düğümlerinin dizisi |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

Bu örnek temelinde [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) kayıtlarını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | Bu örnekteki her nokta için bir [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) ve bir [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) döndürür. |


