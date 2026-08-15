---
title: "IPathShape 클래스"
type: docs
weight: 380
url: /ko/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | Shape가 닫혀 있는지 여부를 결정하는 속성을 가져오거나 설정합니다. |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | 경로 형태 결합(불리언 연산)을 위한 작업입니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_items()](#get_items__1) | Bezier 노드 배열을 가져옵니다. |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Bexier 매듭 배열을 할당합니다. |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

Bezier 노드 배열을 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | BezierKnotRecord 배열. |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Bexier 매듭 배열을 할당합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | 베지어 매듭 배열 |

