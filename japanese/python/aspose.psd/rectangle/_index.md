---
title: "Rectangle クラス"
type: docs
weight: 3810
url: /ja/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Rectangle クラスの新しいインスタンスを初期化します |
| [Rectangle(location, size)](#Rectangle_location_size_2) | 指定された位置とサイズで [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の新しいインスタンスを初期化します。 |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | 指定された位置とサイズで [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bottom | int | r/w | この [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の [Rectangle.y] と [Rectangle.height] プロパティ値の合計である y 座標を取得または設定します。 |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の新しいインスタンスを取得します。このインスタンスは [Rectangle.x]、[Rectangle.y]、[Rectangle.width]、[Rectangle.height] の値がすべてゼロに設定されています。 |
| height | int | r/w | この [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の高さを取得または設定します。 |
| is_empty | bool | r | この [Rectangle](/psd/python-net/aspose.psd/rectangle/) のすべての数値プロパティがゼロであるかどうかを示す値を取得します。 |
| left | int | r/w | この [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の左端の x 座標を取得または設定します。 |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | この [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の左上隅の座標を取得または設定します。 |
| right | int | r/w | この [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の [Rectangle.x] と [Rectangle.width] プロパティ値の合計である x 座標を取得または設定します。 |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | この [Rectangle](/psd/python-net/aspose.psd/rectangle/) のサイズを取得または設定します。 |
| top | int | r/w | この [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の上端の y 座標を取得または設定します。 |
| width | int | r/w | この [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の幅を取得または設定します。 |
| x | int | r/w | この [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の左上隅の x 座標を取得または設定します。 |
| y | int | r/w | この [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の左上隅の y 座標を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | 指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体を、[RectangleF] の値を次の整数に切り上げて [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体に変換します。 |
| [contains(point)](#contains_point_2) | 指定された点がこの [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体に含まれているかどうかを判定します。 |
| [contains(rect)](#contains_rect_3) | <paramref name=\"rect\" /> で表される矩形領域がこの [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体に完全に含まれているかどうかを判定します。 |
| [contains(x, y)](#contains_x_y_4) | 指定された点がこの [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体に含まれているかどうかを判定します。 |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | 指定されたエッジ位置で [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体を作成します。 |
| [from_points(point1, point2)](#from_points_point1_point2_6) | 指定された 2 つの点から新しい [Rectangle](/psd/python-net/aspose.psd/rectangle/) を作成します。作成された [Rectangle] の 2 つの垂直辺は渡された <paramref name=\"point1\" /> と <paramref name=\"point2\" /> に等しくなります。これらは通常、対角の頂点です。 |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | 指定された [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の膨張したコピーを作成して返します。コピーは指定された量だけ膨張します。元の [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体は変更されません。 |
| [inflate(size)](#inflate_size_8) | 指定された量だけこの[Rectangle](/psd/python-net/aspose.psd/rectangle/)を拡大します。 |
| [inflate(width, height)](#inflate_width_height_9) | 指定された量だけこの[Rectangle](/psd/python-net/aspose.psd/rectangle/)を拡大します。 |
| [intersect(a, b)](#intersect_a_b_10) | 2つの他の[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造の交差を表す3番目の[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造を返します。交差がない場合は、空の[Rectangle](/psd/python-net/aspose.psd/rectangle/)が返されます。 |
| [intersect(rect)](#intersect_rect_11) | この[Rectangle](/psd/python-net/aspose.psd/rectangle/)を、自己と指定された[Rectangle](/psd/python-net/aspose.psd/rectangle/)との交差で置き換えます。 |
| [intersects_with(rect)](#intersects_with_rect_12) | この矩形が <paramref name="rect" /> と交差するかどうかを判断します。 |
| normalize() | 矩形の幅と高さを正にし、左が右より小さく、上が下より小さくなるように正規化します。 |
| [offset(pos)](#offset_pos_13) | この矩形の位置を指定された量だけ調整します。 |
| [offset(x, y)](#offset_x_y_14) | この矩形の位置を指定された量だけ調整します。 |
| [round(value)](#round_value_15) | 指定された[RectangleF](/psd/python-net/aspose.psd/rectanglef/)の値を最も近い整数に丸めて、[Rectangle](/psd/python-net/aspose.psd/rectangle/)に変換します。 |
| [truncate(value)](#truncate_value_16) | 指定された[RectangleF](/psd/python-net/aspose.psd/rectanglef/)の値を切り捨てて、[Rectangle](/psd/python-net/aspose.psd/rectangle/)に変換します。 |
| [union(a, b)](#union_a_b_17) | 2つの[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造の合併を含む[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造を取得します。 |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Rectangle クラスの新しいインスタンスを初期化します

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

指定された位置とサイズで [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | 矩形領域の左上隅を表す[Point](/psd/python-net/aspose.psd/point/)です。 |
| size | [Size](/psd/python-net/aspose.psd/size) | 矩形領域の幅と高さを表す[Size](/psd/python-net/aspose.psd/size/)です。 |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

指定された位置とサイズで [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | 矩形の左上隅の x 座標。 |
| y | int | 矩形の左上隅の y 座標。 |
| width | int | 矩形の幅。 |
| 高さ | int | 矩形の高さ。 |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

指定された [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体を、[RectangleF] の値を次の整数に切り上げて [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体に変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 変換される[RectangleF](/psd/python-net/aspose.psd/rectanglef/)構造です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | [Rectangle](/psd/python-net/aspose.psd/rectangle/) を返します。 |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

指定された点がこの [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体に含まれているかどうかを判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | テスト対象の[Point](/psd/python-net/aspose.psd/point/)です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、<paramref name=\"point\" />で表される点がこの[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造内に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

<paramref name=\"rect\" /> で表される矩形領域がこの [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体に完全に含まれているかどうかを判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | テスト対象の[Rectangle](/psd/python-net/aspose.psd/rectangle/)です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、<paramref name=\"rect\" />で表される矩形領域がこの[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造内に完全に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

指定された点がこの [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体に含まれているかどうかを判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | テスト対象の点の x 座標。 |
| y | int | テスト対象の点の y 座標。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、<paramref name=\"x\" /> と <paramref name=\"y\" />で定義された点がこの[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造内に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

指定されたエッジ位置で [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体を作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| left | int | この[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造の左上隅の x 座標です。 |
| top | int | この[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造の左上隅の y 座標です。 |
| right | int | この[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造の右下隅の x 座標です。 |
| bottom | int | この[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造の右下隅の y 座標です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | このメソッドが作成する新しい[Rectangle](/psd/python-net/aspose.psd/rectangle/)です。 |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

指定された 2 つの点から新しい [Rectangle](/psd/python-net/aspose.psd/rectangle/) を作成します。作成された [Rectangle] の 2 つの垂直辺は渡された <paramref name=\"point1\" /> と <paramref name=\"point2\" /> に等しくなります。これらは通常、対角の頂点です。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | 新しい矩形の最初の [Point](/psd/python-net/aspose.psd/point/)。 |
| point2 | [Point](/psd/python-net/aspose.psd/point) | 新しい矩形の2番目の [Point](/psd/python-net/aspose.psd/point/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 新しく作成された [Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

指定された [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体の膨張したコピーを作成して返します。コピーは指定された量だけ膨張します。元の [Rectangle](/psd/python-net/aspose.psd/rectangle/) 構造体は変更されません。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 開始に使用する[Rectangle](/psd/python-net/aspose.psd/rectangle/)です。この矩形は変更されません。 |
| x | int | この[Rectangle](/psd/python-net/aspose.psd/rectangle/)を水平方向に拡大する量です。 |
| y | int | この[Rectangle](/psd/python-net/aspose.psd/rectangle/)を垂直方向に拡大する量です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 拡大された[Rectangle](/psd/python-net/aspose.psd/rectangle/)です。 |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

指定された量だけこの[Rectangle](/psd/python-net/aspose.psd/rectangle/)を拡大します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | この矩形を膨らませる量。 |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

指定された量だけこの[Rectangle](/psd/python-net/aspose.psd/rectangle/)を拡大します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| width | int | この[Rectangle](/psd/python-net/aspose.psd/rectangle/)を水平方向に拡大する量です。 |
| height | int | この[Rectangle](/psd/python-net/aspose.psd/rectangle/)を垂直方向に拡大する量です。 |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

2つの他の[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造の交差を表す3番目の[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造を返します。交差がない場合は、空の[Rectangle](/psd/python-net/aspose.psd/rectangle/)が返されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 最初の交差対象矩形。 |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 2番目の交差対象矩形。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | <paramref name=\"a\" /> と <paramref name=\"b\" />の交差を表す[Rectangle](/psd/python-net/aspose.psd/rectangle/)です。 |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

この[Rectangle](/psd/python-net/aspose.psd/rectangle/)を、自己と指定された[Rectangle](/psd/python-net/aspose.psd/rectangle/)との交差で置き換えます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 交差させるための[Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

この矩形が <paramref name="rect" /> と交差するかどうかを判断します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | テスト対象の矩形。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは交差がある場合は true を返し、そうでない場合は false を返します。 |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

この矩形の位置を指定された量だけ調整します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | 位置をオフセットする量。 |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

この矩形の位置を指定された量だけ調整します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | 水平オフセット。 |
| y | int | 垂直オフセット。 |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

指定された[RectangleF](/psd/python-net/aspose.psd/rectanglef/)の値を最も近い整数に丸めて、[Rectangle](/psd/python-net/aspose.psd/rectangle/)に変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 変換対象の[RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 新しい[Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

指定された[RectangleF](/psd/python-net/aspose.psd/rectanglef/)の値を切り捨てて、[Rectangle](/psd/python-net/aspose.psd/rectangle/)に変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 変換対象の[RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 新しい[Rectangle](/psd/python-net/aspose.psd/rectangle/)。 |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

2つの[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造の合併を含む[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 結合する最初の矩形。 |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 結合する2番目の矩形。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 2つの[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造の合成を囲む[Rectangle](/psd/python-net/aspose.psd/rectangle/)構造。 |


