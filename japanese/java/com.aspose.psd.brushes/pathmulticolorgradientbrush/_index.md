---
title: "PathMulticolorGradientBrush"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "グラデーションを持つ Aspose.Imaging.Brush オブジェクトをカプセル化します。"
type: docs
weight: 16
url: /ja/java/com.aspose.psd.brushes/pathmulticolorgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathMulticolorGradientBrush extends PathGradientBrushBase
```

グラデーションを持つ  Aspose.Imaging.Brush  オブジェクトをカプセル化します。このクラスは継承できません。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PathMulticolorGradientBrush(PointF[] points)](#PathMulticolorGradientBrush-com.aspose.psd.PointF---) | 指定されたポイントで  PathMulticolorGradientBrush  クラスの新しいインスタンスを初期化します。 |
| [PathMulticolorGradientBrush(PointF[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.psd.PointF---int-) | 指定されたポイントとラップモードで  PathMulticolorGradientBrush  クラスの新しいインスタンスを初期化します。 |
| [PathMulticolorGradientBrush(Point[] points)](#PathMulticolorGradientBrush-com.aspose.psd.Point---) | 指定されたポイントで  PathMulticolorGradientBrush  クラスの新しいインスタンスを初期化します。 |
| [PathMulticolorGradientBrush(Point[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.psd.Point---int-) | 指定されたポイントとラップモードで  PathMulticolorGradientBrush  クラスの新しいインスタンスを初期化します。 |
| [PathMulticolorGradientBrush(GraphicsPath path)](#PathMulticolorGradientBrush-com.aspose.psd.GraphicsPath-) | 指定されたパスで  PathMulticolorGradientBrush  クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [deepClone()](#deepClone--) | 現在の Brush の新しいディープクローンを作成します。 |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCenterPoint()](#getCenterPoint--) | パス グラデーションの中心点を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [getFocusScales()](#getFocusScales--) | グラデーションの減衰の焦点を取得します。 |
| [getGraphicsPath()](#getGraphicsPath--) | このブラシが構築されたグラフィック パスを取得します。 |
| [getInterpolationColors()](#getInterpolationColors--) | マルチカラー線形グラデーションを定義する  com.aspose.psd.ColorBlend  を取得または設定します。 |
| [getOpacity()](#getOpacity--) | ブラシの不透明度を取得します。 |
| [getPathPoints()](#getPathPoints--) | このブラシが構築されたパスのポイントを取得します。 |
| [getTransform()](#getTransform--) | この TransformBrush のローカル幾何変換を定義する Aspose.Imaging.Matrix のコピーを取得または設定します。 |
| [getWrapMode()](#getWrapMode--) | この TransformBrush のラップモードを示す Aspose.Imaging.WrapMode 列挙体を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
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
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | パス グラデーションの中心点を取得または設定します。 |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | グラデーションの減衰の焦点を取得または設定します。 |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | マルチカラー線形グラデーションを定義する  com.aspose.psd.ColorBlend  を取得または設定します。 |
| [setOpacity(float value)](#setOpacity-float-) | ブラシの不透明度を設定します。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | この TransformBrush のローカル幾何変換を定義する Aspose.Imaging.Matrix のコピーを取得または設定します。 |
| [setWrapMode(int value)](#setWrapMode-int-) | この TransformBrush のラップモードを示す Aspose.Imaging.WrapMode 列挙体を取得または設定します。 |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | ローカルの幾何変換を指定された寸法だけ平行移動します。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | ローカルの幾何変換を指定された寸法で、指定された順序で平行移動します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathMulticolorGradientBrush(PointF[] points) {#PathMulticolorGradientBrush-com.aspose.psd.PointF---}
```
public PathMulticolorGradientBrush(PointF[] points)
```


指定されたポイントで  PathMulticolorGradientBrush  クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | パスの頂点を構成するポイントを表す  Aspose.Imaging.PointF  構造体の配列です。 |

### PathMulticolorGradientBrush(PointF[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.psd.PointF---int-}
```
public PathMulticolorGradientBrush(PointF[] points, int wrapMode)
```


指定されたポイントとラップモードで  PathMulticolorGradientBrush  クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | パスの頂点を構成するポイントを表す  Aspose.Imaging.PointF  構造体の配列です。 |
| wrapMode | int | この  PathMulticolorGradientBrush で描画された塗りつぶしがどのようにタイル化されるかを指定する  Aspose.Imaging.WrapMode です。 |

### PathMulticolorGradientBrush(Point[] points) {#PathMulticolorGradientBrush-com.aspose.psd.Point---}
```
public PathMulticolorGradientBrush(Point[] points)
```


指定されたポイントで  PathMulticolorGradientBrush  クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | パスの頂点を構成するポイントを表す  Aspose.Imaging.Point  構造体の配列です。 |

### PathMulticolorGradientBrush(Point[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.psd.Point---int-}
```
public PathMulticolorGradientBrush(Point[] points, int wrapMode)
```


指定されたポイントとラップモードで  PathMulticolorGradientBrush  クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | パスの頂点を構成するポイントを表す  Aspose.Imaging.Point  構造体の配列です。 |
| wrapMode | int | この  PathMulticolorGradientBrush で描画された塗りつぶしがどのようにタイル化されるかを指定する  Aspose.Imaging.WrapMode です。 |

### PathMulticolorGradientBrush(GraphicsPath path) {#PathMulticolorGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathMulticolorGradientBrush(GraphicsPath path)
```


指定されたパスで  PathMulticolorGradientBrush  クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | この  PathMulticolorGradientBrush  によって塗りつぶされる領域を定義する  GraphicsPath です。 |

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
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


パス グラデーションの中心点を取得または設定します。

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the center point of the path gradient.
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
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


グラデーションの減衰の焦点を取得します。

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


このブラシが構築されたグラフィック パスを取得します。

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


マルチカラー線形グラデーションを定義する  com.aspose.psd.ColorBlend  を取得または設定します。

値: マルチカラー線形グラデーションを定義する  com.aspose.psd.ColorBlend  。

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend)
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


ブラシの不透明度を取得します。値は 0 から 1 の間である必要があります。0 の場合はブラシが完全に透明で、1 の場合はブラシが完全に不透明です。

**Returns:**
float - ブラシの不透明度の値です。
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


このブラシが構築されたパスのポイントを取得します。

**Returns:**
com.aspose.psd.PointF[] - パスのポイント。
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

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


パス グラデーションの中心点を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | パス グラデーションの中心点を表す  Aspose.Imaging.PointF です。 |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


グラデーションの減衰の焦点を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | グラデーションの減衰の焦点を表す  Aspose.Imaging.PointF です。 |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


マルチカラー線形グラデーションを定義する  com.aspose.psd.ColorBlend  を取得または設定します。

値: マルチカラー線形グラデーションを定義する  com.aspose.psd.ColorBlend  。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


ブラシの不透明度を設定します。値は 0 から 1 の間である必要があります。0 の場合はブラシが完全に透過し、1 の場合は完全に不透明です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | ブラシの不透明度の値です。 |

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

