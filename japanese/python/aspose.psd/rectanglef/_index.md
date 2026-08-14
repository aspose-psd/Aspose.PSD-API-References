---
title: "RectangleF クラス"
type: docs
weight: 3830
url: /ja/python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | RectangleF クラスの新しいインスタンスを初期化します |
| [RectangleF(location, size)](#RectangleF_location_size_2) | 指定された位置とサイズで、[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の新しいインスタンスを初期化します。 |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | 指定された位置とサイズで、[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bottom | float | r/w | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/) と [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) の合計である y 座標を取得または設定します。 |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | すべての [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/)、[RectangleF.y](/psd/python-net/aspose.psd/rectanglef/)、[RectangleF.width](/psd/python-net/aspose.psd/rectanglef/)、[RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) の値が 0 に設定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の新しいインスタンスを取得します。 |
| height | float | r/w | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の高さを取得または設定します。 |
| is_empty | bool | r | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) の [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) または [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) プロパティが 0 の値を持つかどうかを示す値を取得します。 |
| left | float | r/w | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の左端の x 座標を取得または設定します。 |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の左上隅の座標を取得または設定します。 |
| right | float | r/w | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/) と [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) の合計である x 座標を取得または設定します。 |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) のサイズを取得または設定します。 |
| top | float | r/w | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の上端の y 座標を取得または設定します。 |
| width | float | r/w | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の幅を取得または設定します。 |
| x | float | r/w | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の左上隅の x 座標を取得または設定します。 |
| y | float | r/w | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の左上隅の y 座標を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [contains(point)](#contains_point_1) | 指定された点がこの [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体に含まれているかどうかを判断します。 |
| [contains(rect)](#contains_rect_2) | この <paramref name="rect" /> で表される矩形領域が、この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体に完全に含まれているかどうかを判断します。 |
| [contains(x, y)](#contains_x_y_3) | 指定された点がこの [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体に含まれているかどうかを判断します。 |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | 指定された位置に左上隅と右下隅を持つ [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体を作成します。 |
| [from_points(point1, point2)](#from_points_point1_point2_5) | 指定された2つの点から新しい [Rectangle](/psd/python-net/aspose.psd/rectangle/) を作成します。作成された [Rectangle] の2つの頂点は、渡された <paramref name="point1" /> と <paramref name="point2" /> に等しくなります。これらは通常、対角の頂点です。 |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | 指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の膨張したコピーを作成して返します。コピーは指定された量だけ膨張します。元の矩形は変更されません。 |
| [inflate(size)](#inflate_size_7) | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) を指定された量だけ膨張させます。 |
| [inflate(x, y)](#inflate_x_y_8) | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体を指定された量だけ膨張させます。 |
| [intersect(a, b)](#intersect_a_b_9) | 2つの矩形の交差部分を表す [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体を返します。交差がない場合は、空の [RectangleF](/psd/python-net/aspose.psd/rectanglef/) が返されます。 |
| [intersect(rect)](#intersect_rect_10) | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体を、自己と指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体との交差部分に置き換えます。 |
| [intersects_with(rect)](#intersects_with_rect_11) | この矩形が <paramref name="rect" /> と交差するかどうかを判断します。 |
| normalize() | 矩形の幅と高さを正にし、左が右より小さく、上が下より小さくなるように正規化します。 |
| [offset(pos)](#offset_pos_12) | この矩形の位置を指定された量だけ調整します。 |
| [offset(x, y)](#offset_x_y_13) | この矩形の位置を指定された量だけ調整します。 |
| [union(a, b)](#union_a_b_14) | 2つの矩形の合併を形成する、両方を包含できる最小の第3の矩形を作成します。 |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

RectangleF クラスの新しいインスタンスを初期化します

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

指定された位置とサイズで、[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | 矩形領域の左上隅を表す [PointF](/psd/python-net/aspose.psd/pointf/)。 |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | 矩形領域の幅と高さを表す [SizeF](/psd/python-net/aspose.psd/sizef/)。 |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

指定された位置とサイズで、[RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | float | 矩形の左上隅の x 座標。 |
| y | float | 矩形の左上隅の y 座標。 |
| width | float | 矩形の幅。 |
| 高さ | float | 矩形の高さ。 |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

指定された点がこの [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体に含まれているかどうかを判断します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | テスト対象の [PointF](/psd/python-net/aspose.psd/pointf/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、<paramref name="point" /> パラメータで表される点がこの [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体に含まれている場合は true を、そうでない場合は false を返します。 |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

この <paramref name="rect" /> で表される矩形領域が、この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体に完全に含まれているかどうかを判断します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | テスト対象の [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、<paramref name="rect" /> で表される矩形領域が、この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) で表される矩形領域に完全に含まれている場合は true を、そうでない場合は false を返します。 |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

指定された点がこの [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体に含まれているかどうかを判断します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | float | テスト対象の点の x 座標。 |
| y | float | テスト対象の点の y 座標。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、<paramref name="x" /> と <paramref name="y" /> で定義された点がこの [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体に含まれている場合は true を返し、そうでない場合は false を返します。 |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

指定された位置に左上隅と右下隅を持つ [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体を作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 左 | float | 矩形領域の左上隅の x 座標。 |
| top | float | 矩形領域の左上隅の y 座標。 |
| 右 | float | 矩形領域の右下隅の x 座標。 |
| bottom | float | 矩形領域の右下隅の y 座標。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | このメソッドが作成する新しい [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

指定された2つの点から新しい [Rectangle](/psd/python-net/aspose.psd/rectangle/) を作成します。作成された [Rectangle] の2つの頂点は、渡された <paramref name="point1" /> と <paramref name="point2" /> に等しくなります。これらは通常、対角の頂点です。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | 新しい矩形の最初の [Point](/psd/python-net/aspose.psd/point/)。 |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | 新しい矩形の2番目の [Point](/psd/python-net/aspose.psd/point/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 新しく作成された [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体の膨張したコピーを作成して返します。コピーは指定された量だけ膨張します。元の矩形は変更されません。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | コピーされる [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。この矩形は変更されません。 |
| x | float | 矩形のコピーを水平方向に膨らませる量。 |
| y | float | 矩形のコピーを垂直方向に膨らませる量。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 膨らませた [RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) を指定された量だけ膨張させます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | この矩形を膨らませる量。 |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体を指定された量だけ膨張させます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | float | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体を水平方向に膨らませる量。 |
| y | float | この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体を垂直方向に膨らませる量。 |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

2つの矩形の交差部分を表す [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体を返します。交差がない場合は、空の [RectangleF](/psd/python-net/aspose.psd/rectanglef/) が返されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 最初の交差対象矩形。 |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 2番目の交差対象矩形。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 2つの指定された矩形の重なり領域のサイズを表す 3 番目の [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

この [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体を、自己と指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体との交差部分に置き換えます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 交差対象の矩形。 |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

この矩形が <paramref name="rect" /> と交差するかどうかを判断します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | テスト対象の矩形。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、交差がある場合に true を返します。 |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

この矩形の位置を指定された量だけ調整します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | 位置をオフセットする量。 |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

この矩形の位置を指定された量だけ調整します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | float | 位置を水平方向にオフセットする量。 |
| y | float | 位置を垂直方向にオフセットする量。 |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

2つの矩形の合併を形成する、両方を包含できる最小の第3の矩形を作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 結合する最初の矩形。 |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 結合する2番目の矩形。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 結合を形成する2つの矩形の両方を含む3番目の[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造体。 |


