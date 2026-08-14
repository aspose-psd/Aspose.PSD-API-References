---
title: "GraphicsPath クラス"
type: docs
weight: 1570
url: /ja/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | 新しい [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) クラスのインスタンスを初期化します。 |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | 新しい [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) クラスのインスタンスを初期化します。 |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | 新しい [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) クラスのインスタンスを初期化します。 |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | 新しい [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | オブジェクトの境界を取得または設定します。 |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | パス図形を取得します。 |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | 取得または設定する [FillMode](/psd/python-net/aspose.psd/fillmode/) 列挙体で、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の形状の内部がどのように塗りつぶされるかを決定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | 新しい図形を追加します。 |
| [add_figures(figures)](#add_figures_figures_2) | 新しい図形を追加します。 |
| [add_path(adding_path)](#add_path_adding_path_3) | 指定された [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) をこのパスに追加します。 |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | 指定された [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) をこのパスに追加します。 |
| [deep_clone()](#deep_clone__5) | このグラフィックパスのディープクローンを実行します。 |
| flatten() | このパス内の各曲線を連続した直線セグメントのシーケンスに変換します。 |
| [flatten(matrix)](#flatten_matrix_6) | 指定された変換を適用し、次にこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内の各曲線を連続した直線セグメントのシーケンスに変換します。 |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内の各曲線を連続した直線セグメントのシーケンスに変換します。 |
| [get_bounds(matrix)](#get_bounds_matrix_8) | オブジェクトの境界を取得します。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | オブジェクトの境界を取得します。 |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | 指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) で描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。 |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | 指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) で描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。 |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | 指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) と指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。 |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | 指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) と指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。 |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | 指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) で描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。 |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | 指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) で描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。 |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | 指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) と指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。 |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | 指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) と指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。 |
| [is_visible(point)](#is_visible_point_18) | 指定された点がこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内に含まれるかどうかを示します。 |
| [is_visible(point)](#is_visible_point_19) | 指定された点がこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内に含まれるかどうかを示します。 |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | 指定された点がこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内に含まれるかどうかを示します。 |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | 指定された点がこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内に含まれるかどうかを示します。 |
| [is_visible(x, y)](#is_visible_x_y_22) | 指定された点がこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内に含まれるかどうかを示します。 |
| [is_visible(x, y)](#is_visible_x_y_23) | 指定された点がこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内に含まれるかどうかを示します。 |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | 指定された点が、指定された [Graphics](/psd/python-net/aspose.psd/graphics/) の可視クリップ領域内でこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に含まれるかどうかを示します。 |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | 指定された点が、指定された [Graphics](/psd/python-net/aspose.psd/graphics/) の可視クリップ領域内でこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に含まれるかどうかを示します。 |
| [remove_figure(figure)](#remove_figure_figure_26) | 図形を削除します。 |
| [remove_figures(figures)](#remove_figures_figures_27) | 図形を削除します。 |
| reset() | グラフィックパスを空にし、[FillMode](/psd/python-net/aspose.psd/fillmode/) を [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) に設定します。 |
| reverse() | この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の各形状内の図形、シェイプ、ポイントの順序を逆にします。 |
| [transform(transform)](#transform_transform_28) | 指定された変換をシェイプに適用します。 |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | 矩形と平行四辺形で定義されたワープ変換をこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に適用します。 |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | 矩形と平行四辺形で定義されたワープ変換をこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に適用します。 |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | 矩形と平行四辺形で定義されたワープ変換をこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に適用します。 |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | 矩形と平行四辺形で定義されたワープ変換をこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に適用します。 |
| [widen(pen)](#widen_pen_33) | パスに追加のアウトラインを追加します。 |
| [widen(pen, matrix)](#widen_pen_matrix_34) | この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に追加のアウトラインを追加します。 |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | 指定されたペンでこのパスが描画されたときに塗りつぶされる領域を囲む曲線で、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) を置き換えます。 |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

新しい [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) クラスのインスタンスを初期化します。

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

新しい [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | 初期化元の図形。 |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

新しい [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | 初期化元の図形。 |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 塗りつぶしモード。 |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

新しい [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | 塗りつぶしモード。 |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

新しい図形を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | 追加する図形。 |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

新しい図形を追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | 追加する図形。 |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

指定された [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) をこのパスに追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 追加するための[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

指定された [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) をこのパスに追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 追加するための[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)。 |
| 接続 | bool | 追加されたパスの最初の図形がこのパスの最後の図形の一部であるかどうかを指定するブール値です。true の場合、追加されたパスの最初の図形は最後の図形の一部であることを示します。false の場合、追加されたパスの最初の図形は最後の図形と別個であることを示します。 |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

このグラフィックパスのディープクローンを実行します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | GraphicsPath のディープクローンです。 |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

指定された変換を適用し、次にこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内の各曲線を連続した直線セグメントのシーケンスに変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 平坦化する前にこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)を変換するための[Matrix](/psd/python-net/aspose.psd/matrix/)。 |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内の各曲線を連続した直線セグメントのシーケンスに変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 平坦化する前にこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)を変換するための[Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| 平坦度 | float | 曲線とその平坦化近似との間の許容最大誤差を指定します。デフォルト値は 0.25 です。平坦度の値を小さくすると、近似における線分の数が増加します。 |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

オブジェクトの境界を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 境界の前に適用する行列が計算されます。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 推定されたオブジェクトの境界。 |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

オブジェクトの境界を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 境界の前に適用する行列が計算されます。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | オブジェクトに使用するペンです。これによりオブジェクトの境界サイズに影響を与える可能性があります。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 推定されたオブジェクトの境界。 |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) で描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | テストする位置を指定する[PointF](/psd/python-net/aspose.psd/pointf/)。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | テストに使用する[Pen](/psd/python-net/aspose.psd/pen/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点が指定された[Pen](/psd/python-net/aspose.psd/pen/)で描画されたこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の輪郭内に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) で描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | テストする位置を指定する[PointF](/psd/python-net/aspose.psd/pointf/)。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | テストに使用する[Pen](/psd/python-net/aspose.psd/pen/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点が指定された[Pen](/psd/python-net/aspose.psd/pen/)で描画されたこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の輪郭内に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) と指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | テストする位置を指定する[PointF](/psd/python-net/aspose.psd/pointf/)。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | テストに使用する[Pen](/psd/python-net/aspose.psd/pen/)。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 可視性をテストする対象の[Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点が指定された[Pen](/psd/python-net/aspose.psd/pen/)で描画されたこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の輪郭（下部）内に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) と指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | テストする位置を指定する[PointF](/psd/python-net/aspose.psd/pointf/)。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | テストに使用する[Pen](/psd/python-net/aspose.psd/pen/)。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 可視性をテストする対象の[Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点が指定された[Pen](/psd/python-net/aspose.psd/pen/)で描画されたこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の輪郭（下部）内に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) で描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | float | テスト対象の点の x 座標。 |
| y | float | テスト対象の点の y 座標。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | テストに使用する[Pen](/psd/python-net/aspose.psd/pen/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点が指定された[Pen](/psd/python-net/aspose.psd/pen/)で描画されたこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の輪郭内に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) で描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | テスト対象の点の x 座標。 |
| y | int | テスト対象の点の y 座標。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | テストに使用する[Pen](/psd/python-net/aspose.psd/pen/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点が指定された[Pen](/psd/python-net/aspose.psd/pen/)で描画されたこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の輪郭内に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) と指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | float | テスト対象の点の x 座標。 |
| y | float | テスト対象の点の y 座標。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | テストに使用する[Pen](/psd/python-net/aspose.psd/pen/)。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 可視性をテストする対象の[Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点が指定された[Pen](/psd/python-net/aspose.psd/pen/)で描画されたこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の輪郭（下部）内に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

指定された点が、指定された [Pen](/psd/python-net/aspose.psd/pen/) と指定された [Graphics](/psd/python-net/aspose.psd/graphics/) を使用して描画したときに、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) の輪郭（下）内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | テスト対象の点の x 座標。 |
| y | int | テスト対象の点の y 座標。 |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | テストに使用する[Pen](/psd/python-net/aspose.psd/pen/)。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 可視性をテストする対象の[Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点が指定された[Pen](/psd/python-net/aspose.psd/pen/)で描画されたこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の輪郭（下部）内に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

指定された点がこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | テスト対象の点を表す[PointF](/psd/python-net/aspose.psd/pointf/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点がこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の内部に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

指定された点がこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | テスト対象の点を表す[PointF](/psd/python-net/aspose.psd/pointf/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点がこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の内部に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

指定された点がこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | テスト対象の点を表す[PointF](/psd/python-net/aspose.psd/pointf/)。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 可視性をテストする対象の[Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点がこの内部に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

指定された点がこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | テスト対象の点を表す[PointF](/psd/python-net/aspose.psd/pointf/)。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 可視性をテストする対象の[Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点がこの内部に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

指定された点がこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | float | テスト対象の点の x 座標。 |
| y | float | テスト対象の点の y 座標。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点がこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の内部に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

指定された点がこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 内に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | テスト対象の点の x 座標。 |
| y | int | テスト対象の点の y 座標。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点がこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の内部に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

指定された点が、指定された [Graphics](/psd/python-net/aspose.psd/graphics/) の可視クリップ領域内でこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | float | テスト対象の点の x 座標。 |
| y | float | テスト対象の点の y 座標。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 可視性をテストする対象の[Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点がこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の内部に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

指定された点が、指定された [Graphics](/psd/python-net/aspose.psd/graphics/) の可視クリップ領域内でこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に含まれるかどうかを示します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | テスト対象の点の x 座標。 |
| y | int | テスト対象の点の y 座標。 |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | 可視性をテストする対象の[Graphics](/psd/python-net/aspose.psd/graphics/)。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | このメソッドは、指定された点がこの[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)の内部に含まれる場合に true を返し、そうでない場合は false を返します。 |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

図形を削除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | 削除する図形。 |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

図形を削除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | 削除する図形群。 |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

指定された変換をシェイプに適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | 適用する変換です。 |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

矩形と平行四辺形で定義されたワープ変換をこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 矩形 <paramref name=\"srcRect\" /> が変換される平行四辺形を定義する[PointF](/psd/python-net/aspose.psd/pointf/)構造体の配列です。この配列は 3 要素または 4 要素を含めることができます。配列が 3 要素の場合、平行四辺形の右下隅は最初の 3 点から暗黙的に決定されます。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形 <paramref name=\"destPoints\" /> によって定義された平行四辺形へ変換される矩形を表す[RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

矩形と平行四辺形で定義されたワープ変換をこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 矩形 <paramref name=\"srcRect\" /> が変換される平行四辺形を定義する[PointF](/psd/python-net/aspose.psd/pointf/)構造体の配列です。この配列は 3 要素または 4 要素を含めることができます。配列が 3 要素の場合、平行四辺形の右下隅は最初の 3 点から暗黙的に決定されます。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形 <paramref name=\"destPoints\" /> によって定義された平行四辺形へ変換される矩形を表す[RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | パスに適用する幾何変換を指定する[Matrix](/psd/python-net/aspose.psd/matrix/)。 |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

矩形と平行四辺形で定義されたワープ変換をこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 矩形 <paramref name=\"srcRect\" /> が変換される平行四辺形を定義する[PointF](/psd/python-net/aspose.psd/pointf/)構造体の配列です。この配列は 3 要素または 4 要素を含めることができます。配列が 3 要素の場合、平行四辺形の右下隅は最初の 3 点から暗黙的に決定されます。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形 <paramref name=\"destPoints\" /> によって定義された平行四辺形へ変換される矩形を表す[RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | パスに適用する幾何変換を指定する[Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | [WarpMode](/psd/python-net/aspose.psd/warpmode/) 列挙体で、このワープ操作が透視モードか双一次モードかを指定します。 |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

矩形と平行四辺形で定義されたワープ変換をこの [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 矩形 <paramref name=\"srcRect\" /> が変換される平行四辺形を定義する[PointF](/psd/python-net/aspose.psd/pointf/)構造体の配列です。この配列は 3 要素または 4 要素を含めることができます。配列が 3 要素の場合、平行四辺形の右下隅は最初の 3 点から暗黙的に決定されます。 |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 矩形 <paramref name=\"destPoints\" /> によって定義された平行四辺形へ変換される矩形を表す[RectangleF](/psd/python-net/aspose.psd/rectanglef/)。 |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | パスに適用する幾何変換を指定する[Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | [WarpMode](/psd/python-net/aspose.psd/warpmode/) 列挙体で、このワープ操作が透視モードか双一次モードかを指定します。 |
| flatness | float | 結果のパスの平坦度を 0 から 1 の範囲で指定する値です。詳細については、[GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/) メソッドをご参照ください。 |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

パスに追加のアウトラインを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | このメソッドが作成する新しい輪郭と元のパスの輪郭との間の幅を指定する[Pen](/psd/python-net/aspose.psd/pen/)。 |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) に追加のアウトラインを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | このメソッドが作成する新しい輪郭と元のパスの輪郭との間の幅を指定する[Pen](/psd/python-net/aspose.psd/pen/)。 |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | パスを太くする前に適用する変換を指定する[Matrix](/psd/python-net/aspose.psd/matrix/)。 |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

指定されたペンでこのパスが描画されたときに塗りつぶされる領域を囲む曲線で、この [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) を置き換えます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | このメソッドが作成する新しい輪郭と元のパスの輪郭との間の幅を指定する[Pen](/psd/python-net/aspose.psd/pen/)。 |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | パスを太くする前に適用する変換を指定する[Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| 平坦度 | float | 曲線の平滑度を指定する値です。 |

