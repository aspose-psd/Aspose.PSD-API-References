---
title: "IPathShape クラス"
type: docs
weight: 380
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---

**Summary:** The Shape from the knots of the Bezier curve.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPathShape

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| is_closed | bool | r/w | シェイプが閉じているかどうかを決定するプロパティを取得または設定します。 |
| path_operations | [PathOperations](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/pathoperations/) | r/w | パスシェイプの結合（ブール演算）に関する操作です。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_items()](#get_items__1) | Bezier ノットの配列を取得します。 |
| [set_items(bezier_points)](#set_items_bezier_points_2) | Bexier ノットの配列を割り当てます。 |


### Method: get_items() {#get_items__1}


```
 get_items() 
```

Bezier ノットの配列を取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | BezierKnotRecord の配列。 |


### Method: set_items(bezier_points) {#set_items_bezier_points_2}


```
 set_items(bezier_points) 
```

Bexier ノットの配列を割り当てます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bezier_points | [BezierKnotRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/) | ベジエノットの配列 |

