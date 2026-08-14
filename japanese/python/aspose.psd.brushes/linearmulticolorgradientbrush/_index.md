---
title: "LinearMulticolorGradientBrush クラス"
type: docs
weight: 40
url: /ja/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/
---

**Summary:** Represents a [Brush](/psd/python-net/aspose.psd/brush/) with linear gradient defined by multiple colors and appropriate positions. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.LinearMulticolorGradientBrush

**Inheritance:** LinearGradientBrushBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush__1) | デフォルトパラメータで [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。<br/>            開始色は黒、終了色は白、角度は45度、矩形は (0,0) に位置しサイズは (1,1) です。 |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_2) | 指定されたポイントで [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。 |
| [LinearMulticolorGradientBrush(point1, point2)](#LinearMulticolorGradientBrush_point1_point2_3) | 指定されたポイントで [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。 |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_4) | 矩形と向き角度に基づいて [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。 |
| [LinearMulticolorGradientBrush(rect, angle)](#LinearMulticolorGradientBrush_rect_angle_5) | 矩形と向き角度に基づいて [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。 |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6) | 矩形と向き角度に基づいて [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。 |
| [LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)](#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7) | 矩形と向き角度に基づいて [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| 角度 | float | r/w | グラデーション角度を取得または設定します。 |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| gamma_correction | bool | r/w | この [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) に対してガンマ補正が有効かどうかを示す値を取得または設定します。 |
| interpolation_colors | [ColorBlend](/psd/python-net/aspose.psd/colorblend) | r/w | マルチカラー線形グラデーションを定義する [ColorBlend](/psd/python-net/aspose.psd/colorblend/) を取得または設定します。 |
| is_angle_scalable | bool | r/w | この [LinearGradientBrushBase](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) での変換中に [LinearGradientBrushBase.angle](/psd/python-net/aspose.psd.brushes/lineargradientbrushbase/) が変更されるかどうかを示す値を取得または設定します。 |
| is_transform_changed | bool | r | 変換が何らかの形で変更されたかどうかを示す値を取得します。たとえば、変換行列を設定したり、<br/>            変換行列を変更する任意のメソッドを呼び出したりする場合です。このプロパティは GDI+ との下位互換性のために導入されました。 |
| opacity | float | r/w | ブラシの不透明度を取得または設定します。値は 0 から 1 の間である必要があります。0 の値はブラシが完全に透明であることを意味し、1 の値はブラシが完全に不透明であることを意味します。 |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r/w | グラデーションの開始点と終了点を定義する矩形領域を取得または設定します。 |
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
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | ローカル幾何変換を指定された寸法だけ平行移動します。このメソッドは平行移動を変換の先頭に前置します。 |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | ローカル幾何変換を指定された寸法だけ、指定された順序で平行移動します。 |


### Constructor: LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush__1}


```
 LinearMulticolorGradientBrush() 
```

デフォルトパラメータで [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。<br/>            開始色は黒、終了色は白、角度は45度、矩形は (0,0) に位置しサイズは (1,1) です。

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_2}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

指定されたポイントで [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | 線形グラデーションの開始点を表す [Point](/psd/python-net/aspose.psd/point/) 構造体です。 |
| point2 | [Point](/psd/python-net/aspose.psd/point) | 線形グラデーションの終了点を表す [Point](/psd/python-net/aspose.psd/point/) 構造体です。 |

### Constructor: LinearMulticolorGradientBrush(point1, point2) {#LinearMulticolorGradientBrush_point1_point2_3}


```
 LinearMulticolorGradientBrush(point1, point2) 
```

指定されたポイントで [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | 線形グラデーションの開始点を表す [Point](/psd/python-net/aspose.psd/point/) 構造体です。 |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | 線形グラデーションの終了点を表す [Point](/psd/python-net/aspose.psd/point/) 構造体です。 |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_4}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

矩形と向き角度に基づいて [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 線形グラデーションの境界を指定する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体です。 |
| 角度 | float | 勾配の方向線の角度（x 軸から時計回りに測定した度数）です。 |

### Constructor: LinearMulticolorGradientBrush(rect, angle) {#LinearMulticolorGradientBrush_rect_angle_5}


```
 LinearMulticolorGradientBrush(rect, angle) 
```

矩形と向き角度に基づいて [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 線形グラデーションの境界を指定する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体です。 |
| 角度 | float | 勾配の方向線の角度（x 軸から時計回りに測定した度数）です。 |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_6}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

矩形と向き角度に基づいて [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 線形グラデーションの境界を指定する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体です。 |
| 角度 | float | 勾配の方向線の角度（x 軸から時計回りに測定した度数）です。 |
| is_angle_scalable | bool | <c>true</c> に設定すると、この [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) での変換中に角度が変更されます。 |

### Constructor: LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) {#LinearMulticolorGradientBrush_rect_angle_is_angle_scalable_7}


```
 LinearMulticolorGradientBrush(rect, angle, is_angle_scalable) 
```

矩形と向き角度に基づいて [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 線形グラデーションの境界を指定する [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体です。 |
| 角度 | float | 勾配の方向線の角度（x 軸から時計回りに測定した度数）です。 |
| is_angle_scalable | bool | <c>true</c> に設定すると、この [LinearMulticolorGradientBrush](/psd/python-net/aspose.psd.brushes/linearmulticolorgradientbrush/) での変換中に角度が変更されます。 |

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

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

ローカル幾何変換を指定された寸法だけ平行移動します。このメソッドは平行移動を変換の先頭に前置します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 軸における変換の値。 |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


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

