---
title: "LinearGradientBrush"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "Aspose.Imaging.Brush を線形グラデーションでカプセル化します。"
type: docs
weight: 11
url: /ja/java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Aspose.Imaging.Brush を線形グラデーションでカプセル化します。このクラスは継承できません。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | LinearGradientBrush クラスの新しいインスタンスをデフォルトパラメータで初期化します。 |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | LinearGradientBrush クラスの新しいインスタンスを指定されたポイントと色で初期化します。 |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | LinearGradientBrush クラスの新しいインスタンスを指定されたポイントと色で初期化します。 |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | LinearGradientBrush クラスの新しいインスタンスを矩形、開始色と終了色、そして向き角度に基づいて初期化します。 |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | LinearGradientBrush クラスの新しいインスタンスを矩形、開始色と終了色、そして向き角度に基づいて初期化します。 |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | LinearGradientBrush クラスの新しいインスタンスを矩形、開始色と終了色、そして向き角度に基づいて初期化します。 |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | LinearGradientBrush クラスの新しいインスタンスを矩形、開始色と終了色、そして向き角度に基づいて初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [deepClone()](#deepClone--) | 現在の Brush の新しいディープクローンを作成します。 |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | グラデーション角度を取得します。 |
| [getBlend()](#getBlend--) | グラデーションのカスタムフェードオフを定義する位置と係数を指定する Aspose.Imaging.Blend を取得します。 |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [getEndColor()](#getEndColor--) | 終了グラデーションの色を取得します。 |
| [getGammaCorrection()](#getGammaCorrection--) | この LinearGradientBrushBase に対してガンマ補正が有効かどうかを示す値を取得します。 |
| [getInterpolationColors()](#getInterpolationColors--) | マルチカラー線形グラデーションを定義する com.aspose.psd.ColorBlend を取得します。 |
| [getLinearColors()](#getLinearColors--) | グラデーションの開始色と終了色を取得します。 |
| [getOpacity()](#getOpacity--) | ブラシの不透明度を取得します。 |
| [getRectangle()](#getRectangle--) | グラデーションの開始点と終了点を定義する矩形領域を取得します。 |
| [getStartColor()](#getStartColor--) | 開始グラデーションの色を取得します。 |
| [getTransform()](#getTransform--) | この TransformBrush のローカル幾何変換を定義する Aspose.Imaging.Matrix のコピーを取得または設定します。 |
| [getWrapMode()](#getWrapMode--) | この TransformBrush のラップモードを示す Aspose.Imaging.WrapMode 列挙体を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | この LinearGradientBrushBase での変換中に LinearGradientBrushBase.Angle が変更されるかどうかを示す値を取得します。 |
| [isTransformChanged()](#isTransformChanged--) | 変換が何らかの形で変更されたかどうかを示す値を取得します。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | この LinearGradientBrush のローカル幾何変換を表す Aspose.Imaging.Matrix に、指定された Aspose.Imaging.Matrix を前置して掛け算します。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | この LinearGradientBrush のローカル幾何変換を表す Aspose.Imaging.Matrix に、指定された順序で指定された Aspose.Imaging.Matrix を掛け算します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | TransformBrush.Transform プロパティを単位行列にリセットします。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | ローカル幾何変換を指定された量だけ回転させます。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | ローカル幾何変換を指定された順序で指定された量だけ回転させます。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | ローカル幾何変換を指定された量で拡大縮小します。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | ローカル幾何変換を指定された順序で指定された量で拡大縮小します。 |
| [setAngle(float value)](#setAngle-float-) | グラデーション角度を設定します。 |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | この LinearGradientBrushBase での変換中に LinearGradientBrushBase.Angle が変更されるかどうかを示す値を設定します。 |
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | グラデーションのカスタムフェードオフを定義する位置と係数を指定する Aspose.Imaging.Blend を設定します。 |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | 中心色と両端の単一色への線形フェードオフを持つ線形グラデーションを作成します。 |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | 中心色と両端の単一色への線形フェードオフを持つ線形グラデーションを作成します。 |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | 終了グラデーションの色を設定します。 |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | この LinearGradientBrushBase に対してガンマ補正が有効かどうかを示す値を設定します。 |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | マルチカラー線形グラデーションを定義する com.aspose.psd.ColorBlend を設定します。 |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | グラデーションの開始色と終了色を設定します。 |
| [setOpacity(float value)](#setOpacity-float-) | ブラシの不透明度を設定します。 |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | グラデーションの開始点と終了点を定義する矩形領域を設定します。 |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | ベル型曲線に基づくグラデーションの減衰を作成します。 |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | ベル型曲線に基づくグラデーションの減衰を作成します。 |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | 開始グラデーションの色を設定します。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | この TransformBrush のローカル幾何変換を定義する Aspose.Imaging.Matrix のコピーを取得または設定します。 |
| [setWrapMode(int value)](#setWrapMode-int-) | この TransformBrush のラップモードを示す Aspose.Imaging.WrapMode 列挙体を取得または設定します。 |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | ローカルの幾何変換を指定された寸法だけ平行移動します。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | ローカルの幾何変換を指定された寸法で、指定された順序で平行移動します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


デフォルトパラメータで LinearGradientBrush クラスの新しいインスタンスを初期化します。開始色は黒、終了色は白、角度は 45 度で、矩形は (0,0) に位置しサイズは (1,1) です。

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


LinearGradientBrush クラスの新しいインスタンスを指定されたポイントと色で初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | 線形グラデーションの開始点を表す Aspose.Imaging.Point 構造体です。 |
| point2 | [Point](../../com.aspose.psd/point) | 線形グラデーションの終了点を表す Aspose.Imaging.Point 構造体です。 |
| color1 | [Color](../../com.aspose.psd/color) | 線形グラデーションの開始色を表す com.aspose.psd.Color 構造体です。 |
| color2 | [Color](../../com.aspose.psd/color) | 線形グラデーションの終了色を表す com.aspose.psd.Color 構造体です。 |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


LinearGradientBrush クラスの新しいインスタンスを指定されたポイントと色で初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | 線形グラデーションの開始点を表す Aspose.Imaging.PointF 構造体です。 |
| point2 | [PointF](../../com.aspose.psd/pointf) | 線形グラデーションの終了点を表す Aspose.Imaging.PointF 構造体です。 |
| color1 | [Color](../../com.aspose.psd/color) | 線形グラデーションの開始色を表す com.aspose.psd.Color 構造体です。 |
| color2 | [Color](../../com.aspose.psd/color) | 線形グラデーションの終了色を表す com.aspose.psd.Color 構造体です。 |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


LinearGradientBrush クラスの新しいインスタンスを矩形、開始色と終了色、そして向き角度に基づいて初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 線形グラデーションの境界を指定する Aspose.Imaging.RectangleF 構造体です。 |
| color1 | [Color](../../com.aspose.psd/color) | グラデーションの開始色を表す com.aspose.psd.Color 構造体です。 |
| color2 | [Color](../../com.aspose.psd/color) | グラデーションの終了色を表す com.aspose.psd.Color 構造体です。 |
| 角度 | float | グラデーションの方向線の角度で、x 軸から時計回りに測定した度数です。 |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


LinearGradientBrush クラスの新しいインスタンスを矩形、開始色と終了色、そして向き角度に基づいて初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 線形グラデーションの境界を指定する Aspose.Imaging.RectangleF 構造体です。 |
| color1 | [Color](../../com.aspose.psd/color) | グラデーションの開始色を表す com.aspose.psd.Color 構造体です。 |
| color2 | [Color](../../com.aspose.psd/color) | グラデーションの終了色を表す com.aspose.psd.Color 構造体です。 |
| 角度 | float | グラデーションの方向線の角度で、x 軸から時計回りに測定した度数です。 |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


LinearGradientBrush クラスの新しいインスタンスを矩形、開始色と終了色、そして向き角度に基づいて初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 線形グラデーションの境界を指定する Aspose.Imaging.RectangleF 構造体です。 |
| color1 | [Color](../../com.aspose.psd/color) | グラデーションの開始色を表す com.aspose.psd.Color 構造体です。 |
| color2 | [Color](../../com.aspose.psd/color) | グラデーションの終了色を表す com.aspose.psd.Color 構造体です。 |
| 角度 | float | グラデーションの方向線の角度で、x 軸から時計回りに測定した度数です。 |
| isAngleScalable | boolean | true に設定すると、この LinearGradientBrush での変換中に角度が変更されます。 |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


LinearGradientBrush クラスの新しいインスタンスを矩形、開始色と終了色、そして向き角度に基づいて初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 線形グラデーションの境界を指定する Aspose.Imaging.RectangleF 構造体です。 |
| color1 | [Color](../../com.aspose.psd/color) | グラデーションの開始色を表す com.aspose.psd.Color 構造体です。 |
| color2 | [Color](../../com.aspose.psd/color) | グラデーションの終了色を表す com.aspose.psd.Color 構造体です。 |
| 角度 | float | グラデーションの方向線の角度で、x 軸から時計回りに測定した度数です。 |
| isAngleScalable | boolean | true に設定すると、この LinearGradientBrush での変換中に角度が変更されます。 |

### close() {#close--}
```
public void close()
```


Closable インターフェイスを実装し、JDK 1.7 以降の try-with-resources 文で使用できます。このメソッドは単に dispose メソッドを呼び出すだけです。

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


現在の Brush の新しいディープクローンを作成します。

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


現在のインスタンスを破棄します。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public float getAngle()
```


グラデーション角度を取得します。

**Returns:**
float - グラデーションの角度です。
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


グラデーションのカスタムフェードオフを定義する位置と係数を指定する Aspose.Imaging.Blend を取得します。

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


このインスタンスが破棄されているかどうかを示す値を取得します。

**Returns:**
boolean - 破棄されている場合は true、そうでなければ false 。
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


終了グラデーションの色を取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


この LinearGradientBrushBase に対してガンマ補正が有効かどうかを示す値を取得します。

**Returns:**
boolean - この LinearGradientBrushBase でガンマ補正が有効な場合は true、そうでない場合は false です。
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


マルチカラー線形グラデーションを定義する com.aspose.psd.ColorBlend を取得します。

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


グラデーションの開始色と終了色を取得します。

**Returns:**
com.aspose.psd.Color[] - グラデーションの開始色と終了色を表す 2 つの Color 構造体の配列です。
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


ブラシの不透明度を取得します。値は 0 から 1 の間である必要があります。0 の場合はブラシが完全に透明で、1 の場合はブラシが完全に不透明です。

**Returns:**
float - ブラシの不透明度の値です。
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


グラデーションの開始点と終了点を定義する矩形領域を取得します。

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


開始グラデーションの色を取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


この TransformBrush のローカル幾何変換を定義する Aspose.Imaging.Matrix のコピーを取得または設定します。

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


この TransformBrush のラップモードを示す Aspose.Imaging.WrapMode 列挙体を取得または設定します。

**Returns:**
int - この TransformBrush で描画された塗りつぶしがどのようにタイル化されるかを指定する Aspose.Imaging.WrapMode です。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


この LinearGradientBrushBase での変換中に LinearGradientBrushBase.Angle が変更されるかどうかを示す値を取得します。

**Returns:**
boolean - この LinearGradientBrushBase での変換中に LinearGradientBrushBase.Angle が変更された場合は true、そうでない場合は false です。
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


変換が何らかの形で変更されたかどうかを示す値を取得します。たとえば、変換行列を設定したり、変換行列を変更するメソッドを呼び出したりした場合です。このプロパティは GDI+ との下位互換性のために導入されました。

値: 変換が変更された場合は True、そうでない場合は false です。

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


この LinearGradientBrush のローカル幾何変換を表す Aspose.Imaging.Matrix に、指定された Aspose.Imaging.Matrix を前置して掛け算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 幾何変換に掛け合わせる Aspose.Imaging.Matrix です。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


この LinearGradientBrush のローカル幾何変換を表す Aspose.Imaging.Matrix に、指定された順序で指定された Aspose.Imaging.Matrix を掛け算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 幾何変換に掛け合わせる Aspose.Imaging.Matrix です。 |
| order | int | 二つの行列を掛け合わせる順序を指定する Aspose.Imaging.MatrixOrder です。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


TransformBrush.Transform プロパティを単位行列にリセットします。

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


ローカルの幾何変換を指定された量だけ回転させます。このメソッドは回転を変換の先頭に追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度です。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


ローカル幾何変換を指定された順序で指定された量だけ回転させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度です。 |
| order | int | 回転行列を追加するか前に付加するかを指定する Aspose.Imaging.MatrixOrder です。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


指定された量でローカル幾何変換を拡大縮小します。このメソッドは拡大縮小行列を変換の先頭に付加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | x 軸方向に変換を拡大縮小する量です。 |
| sy | float | y 軸方向に変換を拡大縮小する量です。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


ローカル幾何変換を指定された順序で指定された量で拡大縮小します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | x 軸方向に変換を拡大縮小する量です。 |
| sy | float | y 軸方向に変換を拡大縮小する量です。 |
| order | int | 拡大縮小行列を追加するか前に付加するかを指定する Aspose.Imaging.MatrixOrder です。 |

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


グラデーション角度を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | グラデーション角度です。 |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


この LinearGradientBrushBase での変換中に LinearGradientBrushBase.Angle が変更されるかどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | この LinearGradientBrushBase で変換中に LinearGradientBrushBase.Angle が変更された場合は true、そうでなければ false です。 |

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


グラデーションのカスタムフェードオフを定義する位置と係数を指定する Aspose.Imaging.Blend を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | グラデーションのカスタム減衰を表す Aspose.Imaging.Blend です。 |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


中心色と両端の単一色への線形フェードオフを持つ線形グラデーションを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 焦点 | float | 0 から 1 の値で、グラデーションの中心（グラデーションが終了色だけで構成される点）を指定します。 |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


中心色と両端の単一色への線形フェードオフを持つ線形グラデーションを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 焦点 | float | 0 から 1 の値で、グラデーションの中心（グラデーションが終了色だけで構成される点）を指定します。 |
| スケール | float | 0 から 1 の値で、開始色から焦点（終了色）への色の減衰速度を指定します。 |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


終了グラデーションの色を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 終了グラデーションの色です。 |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


この LinearGradientBrushBase に対してガンマ補正が有効かどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | この LinearGradientBrushBase でガンマ補正が有効な場合は true、そうでなければ false です。 |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


マルチカラー線形グラデーションを定義する com.aspose.psd.ColorBlend を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | マルチカラー線形グラデーションを定義する com.aspose.psd.ColorBlend です。 |

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


グラデーションの開始色と終了色を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | グラデーションの開始色と終了色を表す 2 つの Color 構造体の配列です。 |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


ブラシの不透明度を設定します。値は 0 から 1 の間である必要があります。0 の場合はブラシが完全に透過し、1 の場合は完全に不透明です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | ブラシの不透明度の値です。 |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


グラデーションの開始点と終了点を定義する矩形領域を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | グラデーションの開始点と終了点を指定する com.aspose.psd.RectangleF 構造体です。 |

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


ベル型曲線に基づくグラデーションの減衰を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 焦点 | float | 0 から 1 の値で、開始色と終了色が等しくブレンドされる点（グラデーションの中心）を指定します。 |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


ベル型曲線に基づくグラデーションの減衰を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 焦点 | float | 0 から 1 の値で、グラデーションの中心（グラデーションが終了色だけで構成される点）を指定します。 |
| スケール | float | 0 から 1 の値で、焦点からの色の減衰速度を指定します。 |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


開始グラデーションの色を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | 開始グラデーションの色です。 |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


この TransformBrush のローカル幾何変換を定義する Aspose.Imaging.Matrix のコピーを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


この TransformBrush のラップモードを示す Aspose.Imaging.WrapMode 列挙体を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


指定された寸法でローカル幾何変換を平行移動します。このメソッドは平行移動を変換の先頭に付加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 方向の平行移動量です。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


ローカルの幾何変換を指定された寸法で、指定された順序で平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 方向の平行移動量です。 |
| order | int | 平行移動を適用する順序（先頭に付加するか末尾に追加するか）です。 |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

