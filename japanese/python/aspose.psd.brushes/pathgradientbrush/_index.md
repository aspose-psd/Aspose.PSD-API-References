---
title: "PathGradientBrush クラス"
type: docs
weight: 50
url: /ja/python-net/aspose.psd.brushes/pathgradientbrush/
---

**Summary:** Encapsulates a [Brush](/psd/python-net/aspose.psd/brush/) object with a gradient. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.PathGradientBrush

**Inheritance:** PathGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PathGradientBrush(path)](#PathGradientBrush_path_1) | 指定されたパスで [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) クラスの新しいインスタンスを初期化します。 |
| [PathGradientBrush(points)](#PathGradientBrush_points_2) | 指定されたポイントで [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) クラスの新しいインスタンスを初期化します。 |
| [PathGradientBrush(points)](#PathGradientBrush_points_3) | 指定されたポイントで [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) クラスの新しいインスタンスを初期化します。 |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_4) | 指定されたポイントとラップモードで [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) クラスの新しいインスタンスを初期化します。 |
| [PathGradientBrush(points, wrap_mode)](#PathGradientBrush_points_wrap_mode_5) | 指定されたポイントとラップモードで [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| blend | [Blend](/psd/python-net/aspose.psd/blend) | r/w | グラデーションのカスタムフェールオフを定義する位置と係数を指定する [Blend] を取得または設定します。 |
| center_color | [Color](/psd/python-net/aspose.psd/color) | r/w | パスグラデーションの中心の色を取得または設定します。 |
| center_point | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | パス グラデーションの中心点を取得または設定します。 |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| focus_scales | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | グラデーションの減衰に対する焦点を取得または設定します。 |
| graphics_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r | このブラシが構築されたグラフィック パスを取得します。 |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | マルチカラー線形グラデーションを定義する [ColorBlend](/psd/python-net/aspose.psd/colorblend/) を取得または設定します。 |
| is_transform_changed | bool | r | 変換が何らかの形で変更されたかどうかを示す値を取得します。たとえば、変換行列を設定したり、<br/>            変換行列を変更する任意のメソッドを呼び出したりする場合です。このプロパティは GDI+ との下位互換性のために導入されました。 |
| opacity | float | r/w | ブラシの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。0 の値はブラシが完全に透明であることを意味し、1 の値はブラシが完全に不透明であることを意味します。 |
| path_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r | このブラシが構築されたパスのポイントを取得します。 |
| surround_colors | [Color[]](/psd/python-net/aspose.psd/color) | r/w | この [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) が塗りつぶすパスのポイントに対応する色の配列を取得または設定します。 |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | この [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/) のローカル幾何変換を定義するコピー [Matrix](/psd/python-net/aspose.psd/matrix/) を取得または設定します。 |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | この [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/) のラップモードを示す [WrapMode](/psd/python-net/aspose.psd/wrapmode/) 列挙体を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | 現在の [Brush](/psd/python-net/aspose.psd/brush/) の新しいディープクローンを作成します。 |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | この [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) のローカル幾何変換を表す [Matrix](/psd/python-net/aspose.psd/matrix/) に、指定された [Matrix](/psd/python-net/aspose.psd/matrix/) を前置して掛け算します。 |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | この [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) のローカル幾何変換を表す [Matrix](/psd/python-net/aspose.psd/matrix/) に、指定された順序で指定された [Matrix](/psd/python-net/aspose.psd/matrix/) を掛け算します。 |
| reset_transform() | [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) プロパティを単位行列にリセットします。 |
| [rotate_transform(angle)](#rotate_transform_angle_4) | ローカル幾何変換を指定された量だけ回転させます。このメソッドは回転を変換の先頭に前置します。 |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | ローカル幾何変換を指定された量だけ、指定された順序で回転させます。 |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | ローカル幾何変換を指定された量だけ拡大縮小します。このメソッドはスケーリング行列を変換の先頭に前置します。 |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | ローカル幾何変換を指定された量だけ、指定された順序で拡大縮小します。 |
| [set_blend_triangular_shape(focus)](#set_blend_triangular_shape_focus_8) | 中心色と 1 つの周囲色への線形減衰を持つグラデーションを作成します。 |
| [set_blend_triangular_shape(focus, scale)](#set_blend_triangular_shape_focus_scale_9) | 中心色と各周囲色への線形減衰を持つグラデーションを作成します。 |
| [set_sigma_bell_shape(focus)](#set_sigma_bell_shape_focus_10) | パスの中心から境界まで色が変化するグラデーションブラシを作成します。色の遷移は鐘形曲線に基づきます。 |
| [set_sigma_bell_shape(focus, scale)](#set_sigma_bell_shape_focus_scale_11) | パスの中心から境界まで色が変化するグラデーションブラシを作成します。色の遷移は鐘形曲線に基づきます。 |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | ローカル幾何変換を指定された寸法だけ平行移動します。このメソッドは平行移動を変換の先頭に前置します。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | ローカル幾何変換を指定された寸法だけ、指定された順序で平行移動します。 |


### Constructor: PathGradientBrush(path) {#PathGradientBrush_path_1}


```
 PathGradientBrush(path) 
```

指定されたパスで [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | この [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) が塗りつぶす領域を定義する [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) です。 |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_2}


```
 PathGradientBrush(points) 
```

指定されたポイントで [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | パスの頂点を構成するポイントを表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列です。 |

### Constructor: PathGradientBrush(points) {#PathGradientBrush_points_3}


```
 PathGradientBrush(points) 
```

指定されたポイントで [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | パスの頂点を構成するポイントを表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列です。 |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_4}


```
 PathGradientBrush(points, wrap_mode) 
```

指定されたポイントとラップモードで [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | パスの頂点を構成するポイントを表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列です。 |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | この [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) で描画された塗りがタイル状になる方法を指定する [WrapMode](/psd/python-net/aspose.psd/wrapmode/) です。 |

### Constructor: PathGradientBrush(points, wrap_mode) {#PathGradientBrush_points_wrap_mode_5}


```
 PathGradientBrush(points, wrap_mode) 
```

指定されたポイントとラップモードで [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| points | [Point[]](/psd/python-net/aspose.psd/point) | パスの頂点を構成するポイントを表す [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列です。 |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | この [PathGradientBrush](/psd/python-net/aspose.psd.brushes/pathgradientbrush/) で描画された塗りがタイル状になる方法を指定する [WrapMode](/psd/python-net/aspose.psd/wrapmode/) です。 |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

現在の [Brush](/psd/python-net/aspose.psd/brush/) の新しいディープクローンを作成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | この [Brush](/psd/python-net/aspose.psd/brush/) インスタンスのディープクローンである新しい [Brush](/psd/python-net/aspose.psd/brush/) です。 |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

この [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) のローカル幾何変換を表す [Matrix](/psd/python-net/aspose.psd/matrix/) に、指定された [Matrix](/psd/python-net/aspose.psd/matrix/) を前置して掛け算します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 幾何変換に掛けるための [Matrix](/psd/python-net/aspose.psd/matrix/) です。 |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

この [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) のローカル幾何変換を表す [Matrix](/psd/python-net/aspose.psd/matrix/) に、指定された順序で指定された [Matrix](/psd/python-net/aspose.psd/matrix/) を掛け算します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 幾何変換に掛けるための [Matrix](/psd/python-net/aspose.psd/matrix/) です。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 2 つの行列を掛け合わせる順序を指定する [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) です。 |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

ローカル幾何変換を指定された量だけ回転させます。このメソッドは回転を変換の先頭に前置します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 角度 | float | 回転角度です。 |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

ローカル幾何変換を指定された量だけ、指定された順序で回転させます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 角度 | float | 回転角度です。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 回転行列を付加するか前置するかを指定する [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) です。 |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

ローカル幾何変換を指定された量だけ拡大縮小します。このメソッドはスケーリング行列を変換の先頭に前置します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| sx | float | x 軸方向に変換を拡大縮小する量です。 |
| sy | float | y 軸方向に変換を拡大縮小する量です。 |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

ローカル幾何変換を指定された量だけ、指定された順序で拡大縮小します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| sx | float | x 軸方向に変換を拡大縮小する量です。 |
| sy | float | y 軸方向に変換を拡大縮小する量です。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | スケーリング行列を付加するか前置するかを指定する [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) です。 |

### Method: set_blend_triangular_shape(focus) {#set_blend_triangular_shape_focus_8}


```
 set_blend_triangular_shape(focus) 
```

中心色と 1 つの周囲色への線形減衰を持つグラデーションを作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 焦点 | float | 0 から 1 の値で、パスの中心から境界への任意の放射方向において中心色が最も高い強度になる位置を指定します。値 1（既定）はパスの中心に最高強度を配置します。 |

### Method: set_blend_triangular_shape(focus, scale) {#set_blend_triangular_shape_focus_scale_9}


```
 set_blend_triangular_shape(focus, scale) 
```

中心色と各周囲色への線形減衰を持つグラデーションを作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 焦点 | float | 0 から 1 の値で、パスの中心から境界への任意の放射方向において中心色が最も高い強度になる位置を指定します。値 1（既定）はパスの中心に最高強度を配置します。 |
| scale | float | 0 から 1 の値で、境界色と混合される中心色の最大強度を指定します。値 1 は中心色の可能な限り最高の強度をもたらし、既定値です。 |

### Method: set_sigma_bell_shape(focus) {#set_sigma_bell_shape_focus_10}


```
 set_sigma_bell_shape(focus) 
```

パスの中心から境界まで色が変化するグラデーションブラシを作成します。色の遷移は鐘形曲線に基づきます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 焦点 | float | 0 から 1 の値で、パスの中心から境界への任意の放射方向において中心色が最も高い強度になる位置を指定します。値 1（既定）はパスの中心に最高強度を配置します。 |

### Method: set_sigma_bell_shape(focus, scale) {#set_sigma_bell_shape_focus_scale_11}


```
 set_sigma_bell_shape(focus, scale) 
```

パスの中心から境界まで色が変化するグラデーションブラシを作成します。色の遷移は鐘形曲線に基づきます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 焦点 | float | 0 から 1 の値で、パスの中心から境界への任意の放射方向において中心色が最も高い強度になる位置を指定します。値 1（既定）はパスの中心に最高強度を配置します。 |
| scale | float | 0 から 1 の値で、境界色と混合される中心色の最大強度を指定します。値 1 は中心色の可能な限り最高の強度をもたらし、既定値です。 |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

ローカル幾何変換を指定された寸法だけ平行移動します。このメソッドは平行移動を変換の先頭に前置します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 軸における変換の値。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

ローカル幾何変換を指定された寸法だけ、指定された順序で平行移動します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 軸における変換の値。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 変換を適用する順序（前置または後置）。 |

