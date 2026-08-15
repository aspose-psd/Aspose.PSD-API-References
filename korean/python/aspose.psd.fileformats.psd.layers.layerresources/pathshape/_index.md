---
title: "PathShape 클래스"
type: docs
weight: 750
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---

**Summary:** The figure from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PathShape

**Inheritance:** IPathShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PathShape()](#PathShape__1) | 새로운 [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) 클래스 인스턴스를 초기화합니다. |
| [PathShape(length_record, bezier_knot_records)](#PathShape_length_record_bezier_knot_records_2) | 새로운 [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | 이 인스턴스가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | 경로 연산(불리언 연산)을 가져오거나 설정합니다. |
| shape_index | ushort | r/w | 레이어에서 현재 경로 형태의 인덱스를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_items()](#get_items__1) | Bezier 노드 배열을 가져옵니다. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Bezier 노드 배열을 할당합니다. |
| [to_vector_path_records()](#to_vector_path_records__3) | 이 인스턴스를 기반으로 [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) 레코드를 생성합니다. |


### Constructor: PathShape() {#PathShape__1}


```
 PathShape() 
```

새로운 [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) 클래스 인스턴스를 초기화합니다.

### Constructor: PathShape(length_record, bezier_knot_records) {#PathShape_length_record_bezier_knot_records_2}


```
 PathShape(length_record, bezier_knot_records) 
```

새로운 [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| length_record | [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) | 길이 레코드입니다. |
| bezier_knot_records | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | Bezier 노드 레코드입니다. |

### Method: get_items() {#get_items__1}


```
 get_items() 
```

Bezier 노드 배열을 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | BezierKnotRecord 배열 |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Bezier 노드 배열을 할당합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | 베지어 매듭 배열 |

### Method: to_vector_path_records() {#to_vector_path_records__3}


```
 to_vector_path_records() 
```

이 인스턴스를 기반으로 [VectorPathRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) 레코드를 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Core.VectorPaths.VectorPathRecord> | 이 인스턴스의 각 포인트에 대해 하나의 [LengthRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/) 및 [BezierKnotRecord](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/)을 반환합니다. |


