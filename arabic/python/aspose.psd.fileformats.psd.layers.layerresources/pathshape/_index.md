---
title: "الفئة PathShape"
type: docs
weight: 750
url: /ar/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PathShape()](#PathShape__1) | ينشئ مثلاً جديداً من الفئة [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | ينشئ مثلاً جديداً من الفئة [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل مغلقاً. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | يحصل أو يعيّن عمليات المسار (العمليات المنطقية). |
| shape_index | ushort | r/w | يحصل أو يعيّن فهرس شكل المسار الحالي في الطبقة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_items()](#get_items__1) | يحصل على مصفوفة من عقد Bezier. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | يعيّن مصفوفة من عقد Bezier. |
| [to_vector_path_records()](#to_vector_path_records__3) | ينشئ سجلات [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) بناءً على هذا المثيل. |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

ينشئ مثلاً جديداً من الفئة [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

ينشئ مثلاً جديداً من الفئة [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | سجل الطول. |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | سجلات عقد Bezier. |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

يحصل على مصفوفة من عقد Bezier.

**Returns**

| النوع | الوصف |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | مصفوفة من BezierKnotRecord |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

يعيّن مصفوفة من عقد Bezier.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | مصفوفة من عقد بيزيه |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

ينشئ سجلات [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) بناءً على هذا المثيل.

**Returns**

| النوع | الوصف |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | يعيد عنصرًا واحدًا من نوع [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) و[BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) لكل نقطة في هذه الحالة. |


