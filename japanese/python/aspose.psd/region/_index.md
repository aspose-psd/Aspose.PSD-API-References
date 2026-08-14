---
title: "Region クラス"
type: docs
weight: 3870
url: /ja/python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Region()](#Region__1) | 新しい [Region](/psd/python-net/aspose.psd/region/) を初期化します。 |
| [Region(path)](#Region_path_2) | 指定された [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) を使用して新しい [Region](/psd/python-net/aspose.psd/region/) を初期化します。 |
| [Region(rect)](#Region_rect_3) | 指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体から新しい [Region](/psd/python-net/aspose.psd/region/) を初期化します。 |
| [Region(rect)](#Region_rect_4) | 指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体から新しい [Region](/psd/python-net/aspose.psd/region/) を初期化します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [complement(path)](#complement_path_1) | この [Region](/psd/python-net/aspose.psd/region/) を、指定された [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) のうち、この [Region](/psd/python-net/aspose.psd/region/) と交差しない部分を含むように更新します。 |
| [complement(rect)](#complement_rect_2) | この [Region](/psd/python-net/aspose.psd/region/) を、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体のうち、この [Region](/psd/python-net/aspose.psd/region/) と交差しない部分を含むように更新します。 |
| [complement(rect)](#complement_rect_3) | この [Region](/psd/python-net/aspose.psd/region/) を、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体のうち、この [Region](/psd/python-net/aspose.psd/region/) と交差しない部分を含むように更新します。 |
| [complement(region)](#complement_region_4) | この [Region](/psd/python-net/aspose.psd/region/) を、指定された [Region](/psd/python-net/aspose.psd/region/) のうち、この [Region](/psd/python-net/aspose.psd/region/) と交差しない部分を含むように更新します。 |
| [deep_clone()](#deep_clone__5) | この [Region](/psd/python-net/aspose.psd/region/) の正確なディープコピーを作成します。 |
| [exclude(path)](#exclude_path_6) | この [Region](/psd/python-net/aspose.psd/region/) を、指定された [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) と交差しない内部の部分のみを含むように更新します。 |
| [exclude(rect)](#exclude_rect_7) | この [Region](/psd/python-net/aspose.psd/region/) を、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体と交差しない内部の部分のみを含むように更新します。 |
| [exclude(rect)](#exclude_rect_8) | この [Region](/psd/python-net/aspose.psd/region/) を、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体と交差しない内部の部分のみを含むように更新します。 |
| [exclude(region)](#exclude_region_9) | この [Region](/psd/python-net/aspose.psd/region/) を、指定された [Region](/psd/python-net/aspose.psd/region/) と交差しない内部の部分のみを含むように更新します。 |
| [intersect(path)](#intersect_path_10) | この [Region](/psd/python-net/aspose.psd/region/) を、指定された [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) との交差部分に更新します。 |
| [intersect(rect)](#intersect_rect_11) | この [Region](/psd/python-net/aspose.psd/region/) を、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体との交差部分に更新します。 |
| [intersect(rect)](#intersect_rect_12) | この [Region](/psd/python-net/aspose.psd/region/) を、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体との交差部分に更新します。 |
| [intersect(region)](#intersect_region_13) | この [Region](/psd/python-net/aspose.psd/region/) を、指定された [Region](/psd/python-net/aspose.psd/region/) との交差部分に更新します。 |
| [is_empty(g)](#is_empty_g_14) | 指定された描画サーフェス上で、この [Region](/psd/python-net/aspose.psd/region/) の内部が空であるかどうかをテストします。 |
| [is_infinite(g)](#is_infinite_g_15) | 指定された描画サーフェス上で、この [Region](/psd/python-net/aspose.psd/region/) の内部が無限であるかどうかをテストします。 |
| [is_visible(point)](#is_visible_point_16) | 指定された [PointF](/psd/python-net/aspose.psd/pointf/) 構造体がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。 |
| [is_visible(point)](#is_visible_point_17) | 指定された [PointF](/psd/python-net/aspose.psd/pointf/) 構造体がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。 |
| [is_visible(point, g)](#is_visible_point_g_18) | 指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画した場合に、指定された [PointF](/psd/python-net/aspose.psd/pointf/) 構造体がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。 |
| [is_visible(point, g)](#is_visible_point_g_19) | 指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画した場合に、指定された [PointF](/psd/python-net/aspose.psd/pointf/) 構造体がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。 |
| [is_visible(rect)](#is_visible_rect_20) | 指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の任意の部分がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。 |
| [is_visible(rect)](#is_visible_rect_21) | 指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の任意の部分がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。 |
| [is_visible(rect, g)](#is_visible_rect_g_22) | 指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画した場合に、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の任意の部分がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。 |
| [is_visible(rect, g)](#is_visible_rect_g_23) | 指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画した場合に、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の任意の部分がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。 |
| [is_visible(x, y)](#is_visible_x_y_24) | 指定された点がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。 |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | 指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画した場合に、指定された点がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。 |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | 指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画した場合に、指定された点がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。 |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | 指定された矩形の任意の部分がこの[Region](/psd/python-net/aspose.psd/region/)に含まれているかテストします。 |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | 指定された矩形の任意の部分がこの[Region](/psd/python-net/aspose.psd/region/)に含まれているかテストします。 |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | 指定された[Graphics](/psd/python-net/aspose.psd/graphics/)で描画された場合に、指定された矩形の任意の部分がこの[Region](/psd/python-net/aspose.psd/region/)に含まれているかテストします。 |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | 指定された[Graphics](/psd/python-net/aspose.psd/graphics/)で描画された場合に、指定された矩形の任意の部分がこの[Region](/psd/python-net/aspose.psd/region/)に含まれているかテストします。 |
| make_empty() | この[Region](/psd/python-net/aspose.psd/region/)を空の内部に初期化します。 |
| make_infinite() | この[Region](/psd/python-net/aspose.psd/region/)オブジェクトを無限の内部に初期化します。 |
| [transform(matrix)](#transform_matrix_31) | 指定された[Matrix](/psd/python-net/aspose.psd/matrix/)でこの[Region](/psd/python-net/aspose.psd/region/)を変換します。 |
| [translate(dx, dy)](#translate_dx_dy_32) | 指定された量だけこの[Region](/psd/python-net/aspose.psd/region/)の座標をオフセットします。 |
| [translate(dx, dy)](#translate_dx_dy_33) | 指定された量だけこの[Region](/psd/python-net/aspose.psd/region/)の座標をオフセットします。 |
| [union(path)](#union_path_34) | この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の合併に更新します。 |
| [union(rect)](#union_rect_35) | この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体の合併に更新します。 |
| [union(rect)](#union_rect_36) | この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体の合併に更新します。 |
| [union(region)](#union_region_37) | この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[Region](/psd/python-net/aspose.psd/region/)の合併に更新します。 |
| [xor(path)](#xor_path_38) | この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の交差部分を除いた合併に更新します。 |
| [xor(rect)](#xor_rect_39) | この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体の交差部分を除いた合併に更新します。 |
| [xor(rect)](#xor_rect_40) | この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体の交差部分を除いた合併に更新します。 |
| [xor(region)](#xor_region_41) | この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[Region](/psd/python-net/aspose.psd/region/)の交差部分を除いた合併に更新します。 |


### Constructor: Region() {#Region__1}


```
 Region() 
```

新しい [Region](/psd/python-net/aspose.psd/region/) を初期化します。

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

指定された [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) を使用して新しい [Region](/psd/python-net/aspose.psd/region/) を初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 新しい[Region](/psd/python-net/aspose.psd/region/)を定義する[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)です。 |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体から新しい [Region](/psd/python-net/aspose.psd/region/) を初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 新しい[Region](/psd/python-net/aspose.psd/region/)の内部を定義する[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体から新しい [Region](/psd/python-net/aspose.psd/region/) を初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 新しい[Region](/psd/python-net/aspose.psd/region/)の内部を定義する[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

この [Region](/psd/python-net/aspose.psd/region/) を、指定された [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) のうち、この [Region](/psd/python-net/aspose.psd/region/) と交差しない部分を含むように更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | この[Region](/psd/python-net/aspose.psd/region/)を補完する[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)です。 |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

この [Region](/psd/python-net/aspose.psd/region/) を、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体のうち、この [Region](/psd/python-net/aspose.psd/region/) と交差しない部分を含むように更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | この[Region](/psd/python-net/aspose.psd/region/)を補完する[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

この [Region](/psd/python-net/aspose.psd/region/) を、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体のうち、この [Region](/psd/python-net/aspose.psd/region/) と交差しない部分を含むように更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | この[Region](/psd/python-net/aspose.psd/region/)を補完する[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

この [Region](/psd/python-net/aspose.psd/region/) を、指定された [Region](/psd/python-net/aspose.psd/region/) のうち、この [Region](/psd/python-net/aspose.psd/region/) と交差しない部分を含むように更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | この[Region](/psd/python-net/aspose.psd/region/)オブジェクトを補完する[Region](/psd/python-net/aspose.psd/region/)オブジェクトです。 |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

この [Region](/psd/python-net/aspose.psd/region/) の正確なディープコピーを作成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | このメソッドが作成する[Region](/psd/python-net/aspose.psd/region/)です。 |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

この [Region](/psd/python-net/aspose.psd/region/) を、指定された [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) と交差しない内部の部分のみを含むように更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | この[Region](/psd/python-net/aspose.psd/region/)から除外する[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)です。 |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

この [Region](/psd/python-net/aspose.psd/region/) を、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体と交差しない内部の部分のみを含むように更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | この[Region](/psd/python-net/aspose.psd/region/)から除外する[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

この [Region](/psd/python-net/aspose.psd/region/) を、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体と交差しない内部の部分のみを含むように更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | この[Region](/psd/python-net/aspose.psd/region/)から除外する[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

この [Region](/psd/python-net/aspose.psd/region/) を、指定された [Region](/psd/python-net/aspose.psd/region/) と交差しない内部の部分のみを含むように更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | この[Region](/psd/python-net/aspose.psd/region/)から除外する[Region](/psd/python-net/aspose.psd/region/)です。 |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

この [Region](/psd/python-net/aspose.psd/region/) を、指定された [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) との交差部分に更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | この[Region](/psd/python-net/aspose.psd/region/)と交差させる[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)です。 |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

この [Region](/psd/python-net/aspose.psd/region/) を、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体との交差部分に更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | この[Region](/psd/python-net/aspose.psd/region/)と交差させる[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

この [Region](/psd/python-net/aspose.psd/region/) を、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体との交差部分に更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | この[Region](/psd/python-net/aspose.psd/region/)と交差させる[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体です。 |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

この [Region](/psd/python-net/aspose.psd/region/) を、指定された [Region](/psd/python-net/aspose.psd/region/) との交差部分に更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | この[Region](/psd/python-net/aspose.psd/region/)と交差させる[Region](/psd/python-net/aspose.psd/region/)です。 |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

指定された描画サーフェス上で、この [Region](/psd/python-net/aspose.psd/region/) の内部が空であるかどうかをテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 描画面を表す[Graphics](/psd/python-net/aspose.psd/graphics/)です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 変換 <paramref name="g" /> が適用されたとき、この [Region](/psd/python-net/aspose.psd/region/) の内部が空である場合は true、そうでなければ false。 |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

指定された描画サーフェス上で、この [Region](/psd/python-net/aspose.psd/region/) の内部が無限であるかどうかをテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 描画面を表す[Graphics](/psd/python-net/aspose.psd/graphics/)です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 変換 <paramref name="g" /> が適用されたとき、この [Region](/psd/python-net/aspose.psd/region/) の内部が無限である場合は true、そうでなければ false。 |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

指定された [PointF](/psd/python-net/aspose.psd/pointf/) 構造体がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | テスト対象の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <paramref name="point" /> がこの [Region](/psd/python-net/aspose.psd/region/) に含まれる場合は true、そうでなければ false。 |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

指定された [PointF](/psd/python-net/aspose.psd/pointf/) 構造体がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | テスト対象の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <paramref name="point" /> がこの [Region](/psd/python-net/aspose.psd/region/) に含まれる場合は true、そうでなければ false。 |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画した場合に、指定された [PointF](/psd/python-net/aspose.psd/pointf/) 構造体がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | テスト対象の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | グラフィックスコンテキストを表す [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <paramref name="point" /> がこの [Region](/psd/python-net/aspose.psd/region/) に含まれる場合は true、そうでなければ false。 |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画した場合に、指定された [PointF](/psd/python-net/aspose.psd/pointf/) 構造体がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | テスト対象の [PointF](/psd/python-net/aspose.psd/pointf/) 構造体。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | グラフィックスコンテキストを表す [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <paramref name="point" /> がこの [Region](/psd/python-net/aspose.psd/region/) に含まれる場合は true、そうでなければ false。 |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の任意の部分がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | テスト対象の [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <paramref name="rect" /> の一部でもこの [Region](/psd/python-net/aspose.psd/region/) に含まれる場合は true、そうでなければ false。 |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の任意の部分がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | テスト対象の [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <paramref name="rect" /> の一部でもこの [Region](/psd/python-net/aspose.psd/region/) に含まれる場合は true、そうでなければ false。 |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画した場合に、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の任意の部分がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | テスト対象の [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | グラフィックスコンテキストを表す [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <paramref name="rect" /> がこの [Region](/psd/python-net/aspose.psd/region/) に含まれる場合は true、そうでなければ false。 |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画した場合に、指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の任意の部分がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | テスト対象の [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | グラフィックスコンテキストを表す [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <paramref name="rect" /> がこの [Region](/psd/python-net/aspose.psd/region/) に含まれる場合は true、そうでなければ false。 |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

指定された点がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | float | テスト対象の点の x 座標。 |
| y | float | テスト対象の点の y 座標。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定された点がこの [Region](/psd/python-net/aspose.psd/region/) に含まれる場合は True、そうでなければ false。 |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画した場合に、指定された点がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | float | テスト対象の点の x 座標。 |
| y | float | テスト対象の点の y 座標。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | グラフィックスコンテキストを表す [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定された点がこの [Region](/psd/python-net/aspose.psd/region/) に含まれる場合は True、そうでなければ false。 |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画した場合に、指定された点がこの [Region](/psd/python-net/aspose.psd/region/) に含まれているかどうかをテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | テスト対象の点の x 座標。 |
| y | int | テスト対象の点の y 座標。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | グラフィックスコンテキストを表す [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定された点がこの [Region](/psd/python-net/aspose.psd/region/) に含まれる場合は True、そうでなければ false。 |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

指定された矩形の任意の部分がこの[Region](/psd/python-net/aspose.psd/region/)に含まれているかテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | float | テスト対象の矩形の左上隅の x 座標。 |
| y | float | テスト対象の矩形の左上隅の y 座標。 |
| width | float | テスト対象の矩形の幅。 |
| 高さ | float | テスト対象の矩形の高さ。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定された矩形の一部でもこの [Region](/psd/python-net/aspose.psd/region/) オブジェクトに含まれる場合は true、そうでなければ false。 |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

指定された矩形の任意の部分がこの[Region](/psd/python-net/aspose.psd/region/)に含まれているかテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | テスト対象の矩形の左上隅の x 座標。 |
| y | int | テスト対象の矩形の左上隅の y 座標。 |
| width | int | テスト対象の矩形の幅。 |
| 高さ | int | テスト対象の矩形の高さ。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定された矩形の一部でもこの [Region](/psd/python-net/aspose.psd/region/) オブジェクトに含まれる場合は true、そうでなければ false。 |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

指定された[Graphics](/psd/python-net/aspose.psd/graphics/)で描画された場合に、指定された矩形の任意の部分がこの[Region](/psd/python-net/aspose.psd/region/)に含まれているかテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | float | テスト対象の矩形の左上隅の x 座標。 |
| y | float | テスト対象の矩形の左上隅の y 座標。 |
| width | float | テスト対象の矩形の幅。 |
| 高さ | float | テスト対象の矩形の高さ。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | グラフィックスコンテキストを表す [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定された矩形の一部でもこの [Region](/psd/python-net/aspose.psd/region/) に含まれる場合は true、そうでなければ false。 |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

指定された[Graphics](/psd/python-net/aspose.psd/graphics/)で描画された場合に、指定された矩形の任意の部分がこの[Region](/psd/python-net/aspose.psd/region/)に含まれているかテストします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | テスト対象の矩形の左上隅の x 座標。 |
| y | int | テスト対象の矩形の左上隅の y 座標。 |
| width | int | テスト対象の矩形の幅。 |
| 高さ | int | テスト対象の矩形の高さ。 |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | グラフィックスコンテキストを表す [Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定された矩形の一部でもこの [Region](/psd/python-net/aspose.psd/region/) に含まれる場合は true、そうでなければ false。 |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

指定された[Matrix](/psd/python-net/aspose.psd/matrix/)でこの[Region](/psd/python-net/aspose.psd/region/)を変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | この [Region](/psd/python-net/aspose.psd/region/) を変換するための [Matrix](/psd/python-net/aspose.psd/matrix/)。 |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

指定された量だけこの[Region](/psd/python-net/aspose.psd/region/)の座標をオフセットします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dx | float | この [Region](/psd/python-net/aspose.psd/region/) を水平方向にオフセットする量。 |
| dy | float | この [Region](/psd/python-net/aspose.psd/region/) を垂直方向にオフセットする量。 |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

指定された量だけこの[Region](/psd/python-net/aspose.psd/region/)の座標をオフセットします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dx | int | この [Region](/psd/python-net/aspose.psd/region/) を水平方向にオフセットする量。 |
| dy | int | この [Region](/psd/python-net/aspose.psd/region/) を垂直方向にオフセットする量。 |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の合併に更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | この [Region](/psd/python-net/aspose.psd/region/) と結合する [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体の合併に更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | この [Region](/psd/python-net/aspose.psd/region/) と結合する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体の合併に更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | この [Region](/psd/python-net/aspose.psd/region/) と結合する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[Region](/psd/python-net/aspose.psd/region/)の合併に更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | この [Region](/psd/python-net/aspose.psd/region/) と結合する [Region](/psd/python-net/aspose.psd/region/)。 |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の交差部分を除いた合併に更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | この [Region](/psd/python-net/aspose.psd/region/) と排他的論理和 (xor) する [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体の交差部分を除いた合併に更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | この [Region](/psd/python-net/aspose.psd/region/) と排他的論理和 (xor) する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体の交差部分を除いた合併に更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | この [Region](/psd/python-net/aspose.psd/region/) と排他的論理和 (xor) する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

この[Region](/psd/python-net/aspose.psd/region/)を自身と指定された[Region](/psd/python-net/aspose.psd/region/)の交差部分を除いた合併に更新します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | この [Region](/psd/python-net/aspose.psd/region/) と排他的論理和 (xor) する [Region](/psd/python-net/aspose.psd/region/)。 |

