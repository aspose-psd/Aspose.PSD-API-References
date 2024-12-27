---
title: PathShape Class
type: docs
weight: 750
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathShape()](#PathShape__1) | Initializes a new instance of the [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) class. |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | Initializes a new instance of the [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Gets or sets a value indicating whether this instance is closed. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | Gets or sets the path operations (Boolean operations). |
| shape_index | ushort | r/w | Gets or sets the index of current path shape in layer. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_items()](#get_items__1) | Gets array of Bezier knots. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Assigns array of Bezier knots. |
| [to_vector_path_records()](#to_vector_path_records__3) | Creates the [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) records based on this instance. |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

Initializes a new instance of the [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) class.

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

Initializes a new instance of the [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | The length record. |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | The bezier knot records. |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Gets array of Bezier knots.

**Returns**

| Type | Description |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array of BezierKnotRecord |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Assigns array of Bezier knots.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Array of bezier knots |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

Creates the [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) records based on this instance.

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | Returns one [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) and [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) for each point in this instance. |


