---
title: "PathShape クラス"
type: docs
weight: 750
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PathShape()](#PathShape__1) | 新しい [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) クラスのインスタンスを初期化します。 |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | 新しい [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | このインスタンスが閉じているかどうかを示す値を取得または設定します。 |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | パス操作（ブール演算）を取得または設定します。 |
| shape_index | ushort | r/w | レイヤー内の現在のパスシェイプのインデックスを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_items()](#get_items__1) | Bezier ノットの配列を取得します。 |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Bezier ノットの配列を割り当てます。 |
| [to_vector_path_records()](#to_vector_path_records__3) | このインスタンスに基づいて [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) レコードを作成します。 |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

新しい [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) クラスのインスタンスを初期化します。

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

新しい [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | 長さレコードです。 |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Bezier ノットレコードです。 |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Bezier ノットの配列を取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | BezierKnotRecord の配列 |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Bezier ノットの配列を割り当てます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | ベジエノットの配列 |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

このインスタンスに基づいて [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) レコードを作成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | このインスタンスの各ポイントに対して、1つの[LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/)と[BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/)を返します。 |


