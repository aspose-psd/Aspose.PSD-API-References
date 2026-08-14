---
title: "Pen クラス"
type: docs
weight: 3360
url: /ja/python-net/aspose.psd/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Pen

**Inheritance:** TransparencySupporter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | 指定された [Pen.brush](/psd/python-net/aspose.psd/pen/) を使用して、[Pen](/psd/python-net/aspose.psd/pen/) クラスの新しいインスタンスを初期化します。 |
| [Pen(brush, width)](#Pen_brush_width_2) | 指定された [Pen.brush](/psd/python-net/aspose.psd/pen/) と [Pen.width](/psd/python-net/aspose.psd/pen/) を使用して、[Pen](/psd/python-net/aspose.psd/pen/) クラスの新しいインスタンスを初期化します。 |
| [Pen(color)](#Pen_color_3) | 指定された色を使用して、[Pen](/psd/python-net/aspose.psd/pen/) クラスの新しいインスタンスを初期化します。 |
| [Pen(color, width)](#Pen_color_width_4) | 指定された [Pen.color](/psd/python-net/aspose.psd/pen/) と [Pen.width](/psd/python-net/aspose.psd/pen/) プロパティを使用して、[Pen](/psd/python-net/aspose.psd/pen/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/psd/python-net/aspose.psd/penalignment) | r/w | この [Pen](/psd/python-net/aspose.psd/pen/) の配置を取得または設定します。 |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | r/w | この [Pen](/psd/python-net/aspose.psd/pen/) の属性を決定する [Pen.brush](/psd/python-net/aspose.psd/pen/) を取得または設定します。 |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | この [Pen](/psd/python-net/aspose.psd/pen/) の色を取得または設定します。 |
| compound_array | float | r/w | 複合ペンを指定する値の配列を取得または設定します。複合ペンは、平行線と間隔からなる複合線を描画します。 |
| custom_end_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | この [Pen](/psd/python-net/aspose.psd/pen/) で描画された線の終端に使用するカスタムキャップを取得または設定します。 |
| custom_start_cap | [CustomLineCap](/psd/python-net/aspose.psd/customlinecap) | r/w | この [Pen](/psd/python-net/aspose.psd/pen/) で描画された線の開始点に使用するカスタムキャップを取得または設定します。 |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | r/w | この [Pen](/psd/python-net/aspose.psd/pen/) で描画された破線を構成するダッシュの終端で使用されるキャップスタイルを取得または設定します。 |
| dash_offset | float | r/w | 線の開始点から破線パターンの開始までの距離を取得または設定します。 |
| dash_pattern | float | r/w | カスタムの破線とスペースの配列を取得または設定します。 |
| dash_style | [DashStyle](/psd/python-net/aspose.psd/dashstyle) | r/w | この[Pen](/psd/python-net/aspose.psd/pen/)で描画された破線のスタイルを取得または設定します。 |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | この[Pen](/psd/python-net/aspose.psd/pen/)で描画された線の終端で使用されるキャップスタイルを取得または設定します。 |
| line_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | この[Pen](/psd/python-net/aspose.psd/pen/)で描画された2つの連続した線の端の結合スタイルを取得または設定します。 |
| miter_limit | float | r/w | 斜め角の結合部の厚さの上限を取得または設定します。 |
| opacity | float | r/w | オブジェクトの不透明度を取得または設定します。値は0から1の間である必要があります。0 の値はオブジェクトが完全に可視であることを意味し、1 の値はオブジェクトが完全に不透明であることを意味します。 |
| pen_type | [PenType](/psd/python-net/aspose.psd/pentype) | r | この[Pen](/psd/python-net/aspose.psd/pen/)で描画された線のスタイルを取得します。 |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | この[Pen](/psd/python-net/aspose.psd/pen/)で描画された線の開始点で使用されるキャップスタイルを取得または設定します。 |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | この[Pen](/psd/python-net/aspose.psd/pen/)の幾何変換のコピーを取得または設定します。 |
| width | float | r/w | 描画に使用されるGraphicsオブジェクトの単位で、この[Pen](/psd/python-net/aspose.psd/pen/)の幅を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_1) | この[Pen](/psd/python-net/aspose.psd/pen/)の変換行列に、指定された[Matrix](/psd/python-net/aspose.psd/matrix/)を掛け合わせます。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_2) | この[Pen](/psd/python-net/aspose.psd/pen/)の変換行列に、指定された順序で指定された[Matrix](/psd/python-net/aspose.psd/matrix/)を掛け合わせます。 |
| reset_transform() | この[Pen](/psd/python-net/aspose.psd/pen/)の幾何変換行列を単位行列にリセットします。 |
| [rotate_transform(angle)](#rotate_transform_angle_3) | 指定された角度でローカルの幾何変換を回転させます。このメソッドは回転を変換の先頭に追加します。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_4) | 指定された順序で、指定された角度によりローカルの幾何変換を回転させます。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_5) | 指定された係数でローカルの幾何変換を拡大縮小します。このメソッドは拡大縮小行列を変換の先頭に追加します。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_6) | 指定された順序で、指定された係数によりローカルの幾何変換を拡大縮小します。 |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_7) | この[Pen](/psd/python-net/aspose.psd/pen/)で描画された線の終端に使用されるキャップスタイルを決定する値を設定します。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | 指定された寸法でローカルの幾何変換を平行移動します。このメソッドは平行移動を変換の先頭に追加します。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | 指定された順序で、指定された寸法によりローカルの幾何変換を平行移動します。 |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

指定された [Pen.brush](/psd/python-net/aspose.psd/pen/) を使用して、[Pen](/psd/python-net/aspose.psd/pen/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | この[Pen](/psd/python-net/aspose.psd/pen/)の塗りプロパティを決定する[Pen.brush](/psd/python-net/aspose.psd/pen/)です。 |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

指定された [Pen.brush](/psd/python-net/aspose.psd/pen/) と [Pen.width](/psd/python-net/aspose.psd/pen/) を使用して、[Pen](/psd/python-net/aspose.psd/pen/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brush | [Brush](/psd/python-net/aspose.psd/brush) | この[Pen](/psd/python-net/aspose.psd/pen/)の特性を決定する[Pen.brush](/psd/python-net/aspose.psd/pen/)です。 |
| width | float | 新しい[Pen](/psd/python-net/aspose.psd/pen/)の幅。 |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

指定された色を使用して、[Pen](/psd/python-net/aspose.psd/pen/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | この[Pen](/psd/python-net/aspose.psd/pen/)の色を示す[Pen.color](/psd/python-net/aspose.psd/pen/)構造体。 |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

指定された [Pen.color](/psd/python-net/aspose.psd/pen/) と [Pen.width](/psd/python-net/aspose.psd/pen/) プロパティを使用して、[Pen](/psd/python-net/aspose.psd/pen/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | この[Pen](/psd/python-net/aspose.psd/pen/)の色を示す[Pen.color](/psd/python-net/aspose.psd/pen/)構造体。 |
| width | float | この[Pen](/psd/python-net/aspose.psd/pen/)の幅を示す値。 |

### Method: multiply_transform(matrix) {#multiply_transform_matrix_1}


```
 multiply_transform(matrix) 
```

この[Pen](/psd/python-net/aspose.psd/pen/)の変換行列に、指定された[Matrix](/psd/python-net/aspose.psd/matrix/)を掛け合わせます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 変換行列を乗算するための[Matrix](/psd/python-net/aspose.psd/matrix/)オブジェクト。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_2}


```
 multiply_transform(matrix, order) 
```

この[Pen](/psd/python-net/aspose.psd/pen/)の変換行列に、指定された順序で指定された[Matrix](/psd/python-net/aspose.psd/matrix/)を掛け合わせます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 変換行列を乗算するための[Matrix](/psd/python-net/aspose.psd/matrix/)。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 乗算操作を実行する順序。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_3}


```
 rotate_transform(angle) 
```

指定された角度でローカルの幾何変換を回転させます。このメソッドは回転を変換の先頭に追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 角度 | float | 回転角度です。 |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_4}


```
 rotate_transform(angle, order) 
```

指定された順序で、指定された角度によりローカルの幾何変換を回転させます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 角度 | float | 回転角度です。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 回転行列を付加するか前置するかを指定する [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) です。 |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_5}


```
 scale_transform(sx, sy) 
```

指定された係数でローカルの幾何変換を拡大縮小します。このメソッドは拡大縮小行列を変換の先頭に追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| sx | float | x軸方向に変換を拡大縮小する係数。 |
| sy | float | y軸方向に変換を拡大縮小する係数。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_6}


```
 scale_transform(sx, sy, order) 
```

指定された順序で、指定された係数によりローカルの幾何変換を拡大縮小します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| sx | float | x軸方向に変換を拡大縮小する係数。 |
| sy | float | y軸方向に変換を拡大縮小する係数。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | スケーリング行列を付加するか前置するかを指定する [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) です。 |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_7}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

この[Pen](/psd/python-net/aspose.psd/pen/)で描画された線の終端に使用されるキャップスタイルを決定する値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | この[Pen](/psd/python-net/aspose.psd/pen/)で描画された線の開始点で使用するキャップスタイルを表す[LineCap](/psd/python-net/aspose.psd/linecap/)。 |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | この[Pen](/psd/python-net/aspose.psd/pen/)で描画された線の終点で使用するキャップスタイルを表す[LineCap](/psd/python-net/aspose.psd/linecap/)。 |
| dash_cap | [DashCap](/psd/python-net/aspose.psd/dashcap) | この[Pen](/psd/python-net/aspose.psd/pen/)で描画された破線の開始点または終点で使用するキャップスタイルを表す[LineCap](/psd/python-net/aspose.psd/linecap/)。 |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

指定された寸法でローカルの幾何変換を平行移動します。このメソッドは平行移動を変換の先頭に追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 軸における変換の値。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

指定された順序で、指定された寸法によりローカルの幾何変換を平行移動します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 軸における変換の値。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 変換を適用する順序（前置または後置）。 |

