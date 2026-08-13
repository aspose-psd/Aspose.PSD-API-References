---
title: "PathShape 类"
type: docs
weight: 750
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PathShape()](#PathShape__1) | 初始化 [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) 类的新实例。 |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | 初始化 [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| is_closed | bool | 读/写 | 获取或设置一个值，指示此实例是否已关闭。 |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | 获取或设置路径操作（布尔操作）。 |
| shape_index | ushort | 读/写 | 获取或设置当前图层中路径形状的索引。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_items()](#get_items__1) | 获取贝塞尔节点数组。 |
| [set_items(bezier_points)](#set_items_bezier_points_2) | 分配贝塞尔节点数组。 |
| [to_vector_path_records()](#to_vector_path_records__3) | 基于此实例创建 [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) 记录。 |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

初始化 [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) 类的新实例。

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

初始化 [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | 长度记录。 |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | 贝塞尔节点记录。 |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

获取贝塞尔节点数组。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | BezierKnotRecord 数组 |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

分配贝塞尔节点数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | 贝塞尔节点数组 |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

基于此实例创建 [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) 记录。

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | 返回一个 [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) 和 [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/)，针对该实例中的每个点。 |


