---
title: "RectangleF"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "矩形の位置とサイズを表す 4 つの浮動小数点数のセットを格納します。"
type: docs
weight: 89
url: /ja/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

矩形の位置とサイズを表す 4 つの浮動小数点数のセットを格納します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | 指定された位置とサイズで com.aspose.psd.RectangleF 構造体の新しいインスタンスを初期化します。 |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | 指定された位置とサイズで com.aspose.psd.RectangleF 構造体の新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | 指定されたポイントがこの com.aspose.psd.RectangleF 構造体に含まれているかどうかを判断します。 |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | rect が表す矩形領域が、この com.aspose.psd.RectangleF 構造体に完全に含まれているかどうかを判断します。 |
| [contains(float x, float y)](#contains-float-float-) | 指定されたポイントがこの com.aspose.psd.RectangleF 構造体に含まれているかどうかを判断します。 |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | 現在の矩形値を分割して変換行列の垂直および水平スケール値を変換し、結果の値を持つ新しい [RectangleF](../../com.aspose.psd/rectanglef) インスタンスを返します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | obj がこの com.aspose.psd.RectangleF と同じ位置とサイズを持つ com.aspose.psd.RectangleF かどうかをテストします。 |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | 指定された位置に左上隅と右下隅を持つ com.aspose.psd.RectangleF 構造体を作成します。 |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | 指定された2点から新しい Rectangle を作成します。 |
| [getBottom()](#getBottom--) | この com.aspose.psd.RectangleF 構造体の com.aspose.psd.RectangleF.Y と com.aspose.psd.RectangleF.Height の合計である y 座標を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | com.aspose.psd.RectangleF.X、com.aspose.psd.RectangleF.Y、com.aspose.psd.RectangleF.Width、com.aspose.psd.RectangleF.Height の値がすべてゼロに設定された com.aspose.psd.RectangleF 構造体の新しいインスタンスを取得します。 |
| [getHeight()](#getHeight--) | この com.aspose.psd.RectangleF 構造体の高さを取得または設定します。 |
| [getLeft()](#getLeft--) | この com.aspose.psd.RectangleF 構造体の左端の x 座標を取得または設定します。 |
| [getLocation()](#getLocation--) | この com.aspose.psd.RectangleF 構造体の左上隅の座標を取得または設定します。 |
| [getRight()](#getRight--) | この com.aspose.psd.RectangleF 構造体の com.aspose.psd.RectangleF.X と com.aspose.psd.RectangleF.Width の合計である x 座標を取得または設定します。 |
| [getSize()](#getSize--) | この com.aspose.psd.RectangleF のサイズを取得または設定します。 |
| [getTop()](#getTop--) | この com.aspose.psd.RectangleF 構造体の上端の y 座標を取得または設定します。 |
| [getWidth()](#getWidth--) | この com.aspose.psd.RectangleF 構造体の幅を取得または設定します。 |
| [getX()](#getX--) | この com.aspose.psd.RectangleF 構造体の左上隅の x 座標を取得または設定します。 |
| [getY()](#getY--) | この com.aspose.psd.RectangleF 構造体の左上隅の y 座標を取得または設定します。 |
| [hashCode()](#hashCode--) | この com.aspose.psd.RectangleF 構造体のハッシュコードを取得します。 |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | 指定された com.aspose.psd.RectangleF 構造体の拡張コピーを作成して返します。 |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | この com.aspose.psd.RectangleF を指定された量だけ拡張します。 |
| [inflate(float x, float y)](#inflate-float-float-) | この com.aspose.psd.RectangleF 構造体を指定された量だけ拡張します。 |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | この com.aspose.psd.RectangleF 構造体を、それ自身と指定された com.aspose.psd.RectangleF 構造体との交差部分に置き換えます。 |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | 2 つの矩形の交差を表す com.aspose.psd.RectangleF 構造体を返します。 |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | この矩形が rect と交差するかどうかを判定します。 |
| [isEmpty()](#isEmpty--) | この com.aspose.psd.RectangleF の com.aspose.psd.RectangleF.Width または com.aspose.psd.RectangleF.Height プロパティがゼロであるかどうかを示す値を取得します。 |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | 現在の矩形の値を掛け算して変換行列の垂直および水平スケール値を変換し、結果の値を持つ新しい [RectangleF](../../com.aspose.psd/rectanglef) インスタンスを返します。 |
| [normalize()](#normalize--) | 矩形の幅と高さを正にし、左が右より小さく、上が下より小さくなるように正規化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | この矩形の位置を指定された量だけ調整します。 |
| [offset(float x, float y)](#offset-float-float-) | この矩形の位置を指定された量だけ調整します。 |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | / 演算子を実装します。 |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | 2 つの com.aspose.psd.RectangleF 構造体が位置とサイズが等しいかどうかをテストします。 |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | 2 つの com.aspose.psd.RectangleF 構造体が位置またはサイズが異なるかどうかをテストします。 |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | \* 演算子を実装します。 |
| [setBottom(float value)](#setBottom-float-) | この com.aspose.psd.RectangleF 構造体の com.aspose.psd.RectangleF.Y と com.aspose.psd.RectangleF.Height の合計である y 座標を取得または設定します。 |
| [setHeight(float value)](#setHeight-float-) | この com.aspose.psd.RectangleF 構造体の高さを取得または設定します。 |
| [setLeft(float value)](#setLeft-float-) | この com.aspose.psd.RectangleF 構造体の左端の x 座標を取得または設定します。 |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | この com.aspose.psd.RectangleF 構造体の左上隅の座標を取得または設定します。 |
| [setRight(float value)](#setRight-float-) | この com.aspose.psd.RectangleF 構造体の com.aspose.psd.RectangleF.X と com.aspose.psd.RectangleF.Width の合計である x 座標を取得または設定します。 |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | この com.aspose.psd.RectangleF のサイズを取得または設定します。 |
| [setTop(float value)](#setTop-float-) | この com.aspose.psd.RectangleF 構造体の上端の y 座標を取得または設定します。 |
| [setWidth(float value)](#setWidth-float-) | この com.aspose.psd.RectangleF 構造体の幅を取得または設定します。 |
| [setX(float value)](#setX-float-) | この com.aspose.psd.RectangleF 構造体の左上隅の x 座標を取得または設定します。 |
| [setY(float value)](#setY-float-) | この com.aspose.psd.RectangleF 構造体の左上隅の y 座標を取得または設定します。 |
| [toRectangle_internalized()](#toRectangle-internalized--) | [RectangleF](../../com.aspose.psd/rectanglef) を切り捨てた矩形値を持つ [Rectangle](../../com.aspose.psd/rectangle) 構造体に変換します。 |
| [toString()](#toString--) | この com.aspose.psd.RectangleF の属性を人間が読みやすい文字列に変換します。 |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | 指定された  com.aspose.psd.Rectangle  構造体を  com.aspose.psd.RectangleF  構造体に変換します。 |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | 2つの矩形の合併を形成する両方を含むことができる、可能な限り最小の3番目の矩形を作成します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


指定された位置とサイズで com.aspose.psd.RectangleF 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 矩形の左上隅の x 座標です。 |
| y | float | 矩形の左上隅の y 座標です。 |
| 幅 | float | 矩形の幅です。 |
| 高さ | float | 矩形の高さです。 |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


指定された位置とサイズで com.aspose.psd.RectangleF 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | 矩形領域の左上隅を表す  com.aspose.psd.PointF  です。 |
| size | [SizeF](../../com.aspose.psd/sizef) | 矩形領域の幅と高さを表す  com.aspose.psd.SizeF  です。 |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


指定されたポイントがこの com.aspose.psd.RectangleF 構造体に含まれているかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | テスト対象の  com.aspose.psd.PointF  です。 |

**Returns:**
boolean - このメソッドは、point パラメーターで表される点がこの  com.aspose.psd.RectangleF  構造体に含まれている場合は true を返し、そうでない場合は false を返します。
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


rect が表す矩形領域が、この com.aspose.psd.RectangleF 構造体に完全に含まれているかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | テスト対象の  com.aspose.psd.RectangleF  です。 |

**Returns:**
boolean - このメソッドは、rect で表される矩形領域がこの  com.aspose.psd.RectangleF  で表される矩形領域に完全に含まれている場合は true を返し、そうでない場合は false を返します。
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


指定されたポイントがこの com.aspose.psd.RectangleF 構造体に含まれているかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | テスト対象の点の x 座標です。 |
| y | float | テスト対象の点の y 座標です。 |

**Returns:**
boolean - x と y で定義された点がこの  com.aspose.psd.RectangleF  構造体に含まれている場合は true を返し、そうでない場合は false を返します。
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| size | [SizeF](../../com.aspose.psd/sizef) |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### divideToTransformMatrix_internalized(double[] transformMatrix) {#divideToTransformMatrix-internalized-double---}
```
public final RectangleF divideToTransformMatrix_internalized(double[] transformMatrix)
```


現在の矩形値を分割して変換行列の垂直および水平スケール値を変換し、結果の値を持つ新しい [RectangleF](../../com.aspose.psd/rectanglef) インスタンスを返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| transformMatrix | double[] | レイヤーの変換行列です。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


obj がこの com.aspose.psd.RectangleF と同じ位置とサイズを持つ com.aspose.psd.RectangleF かどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | テスト対象の  System.Object  です。 |

**Returns:**
boolean - obj が  com.aspose.psd.RectangleF  であり、その X、Y、Width、Height プロパティがこの  com.aspose.psd.RectangleF  の対応するプロパティと等しい場合は true を返し、そうでない場合は false を返します。
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


指定された位置に左上隅と右下隅を持つ com.aspose.psd.RectangleF 構造体を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | float | 矩形領域の左上隅の x 座標です。 |
| top | float | 矩形領域の左上隅の y 座標です。 |
| right | float | 矩形領域の右下隅の x 座標です。 |
| 下 | float | 矩形領域の右下隅の y 座標です。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


指定された 2 つの点から新しい Rectangle を作成します。作成された Rectangle の 2 つの頂点は、渡された point1 と point2 に等しくなります。これらは通常、対角の頂点です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | 新しい矩形の最初の Point です。 |
| point2 | [PointF](../../com.aspose.psd/pointf) | 新しい矩形の2番目の Point です。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


この com.aspose.psd.RectangleF 構造体の com.aspose.psd.RectangleF.Y と com.aspose.psd.RectangleF.Height の合計である y 座標を取得または設定します。

**Returns:**
float - この com.aspose.psd.RectangleF 構造体の com.aspose.psd.RectangleF.Y と com.aspose.psd.RectangleF.Height の合計である y 座標です。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


com.aspose.psd.RectangleF.X、com.aspose.psd.RectangleF.Y、com.aspose.psd.RectangleF.Width、com.aspose.psd.RectangleF.Height の値がすべてゼロに設定された com.aspose.psd.RectangleF 構造体の新しいインスタンスを取得します。

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


この com.aspose.psd.RectangleF 構造体の高さを取得または設定します。

**Returns:**
float - この com.aspose.psd.RectangleF 構造体の高さです。
### getLeft() {#getLeft--}
```
public float getLeft()
```


この com.aspose.psd.RectangleF 構造体の左端の x 座標を取得または設定します。

**Returns:**
float - この com.aspose.psd.RectangleF 構造体の左端の x 座標です。
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


この com.aspose.psd.RectangleF 構造体の左上隅の座標を取得または設定します。

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


この com.aspose.psd.RectangleF 構造体の com.aspose.psd.RectangleF.X と com.aspose.psd.RectangleF.Width の合計である x 座標を取得または設定します。

**Returns:**
float - この com.aspose.psd.RectangleF 構造体の com.aspose.psd.RectangleF.X と com.aspose.psd.RectangleF.Width の合計である x 座標です。
### getSize() {#getSize--}
```
public SizeF getSize()
```


この com.aspose.psd.RectangleF のサイズを取得または設定します。

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


この com.aspose.psd.RectangleF 構造体の上端の y 座標を取得または設定します。

**Returns:**
float - この com.aspose.psd.RectangleF 構造体の上端の y 座標です。
### getWidth() {#getWidth--}
```
public float getWidth()
```


この com.aspose.psd.RectangleF 構造体の幅を取得または設定します。

**Returns:**
float - この com.aspose.psd.RectangleF 構造体の幅です。
### getX() {#getX--}
```
public float getX()
```


この com.aspose.psd.RectangleF 構造体の左上隅の x 座標を取得または設定します。

**Returns:**
float - この com.aspose.psd.RectangleF 構造体の左上隅の x 座標です。
### getY() {#getY--}
```
public float getY()
```


この com.aspose.psd.RectangleF 構造体の左上隅の y 座標を取得または設定します。

**Returns:**
float - この com.aspose.psd.RectangleF 構造体の左上隅の y 座標です。
### hashCode() {#hashCode--}
```
public int hashCode()
```


この com.aspose.psd.RectangleF 構造体のハッシュコードを取得します。

**Returns:**
int - この com.aspose.psd.RectangleF のハッシュコードです。
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


指定された com.aspose.psd.RectangleF 構造体の拡張コピーを作成して返します。コピーは指定された量だけ拡張されます。元の矩形は変更されません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | コピー対象の com.aspose.psd.RectangleF です。この矩形は変更されません。 |
| x | float | 矩形のコピーを水平方向に拡張する量です。 |
| y | float | 矩形のコピーを垂直方向に拡張する量です。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


この com.aspose.psd.RectangleF を指定された量だけ拡張します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | この矩形を拡張する量です。 |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


この com.aspose.psd.RectangleF 構造体を指定された量だけ拡張します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | この com.aspose.psd.RectangleF 構造体を水平方向に拡張する量です。 |
| y | float | この com.aspose.psd.RectangleF 構造体を垂直方向に拡張する量です。 |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


この com.aspose.psd.RectangleF 構造体を、それ自身と指定された com.aspose.psd.RectangleF 構造体との交差部分に置き換えます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 交差させる矩形です。 |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


2つの矩形の交差を表す com.aspose.psd.RectangleF 構造体を返します。交差がない場合は、空の com.aspose.psd.RectangleF が返されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | 交差させる最初の矩形です。 |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | 交差させる2番目の矩形です。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


この矩形が rect と交差するかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | テストする矩形。 |

**Returns:**
boolean - 交差がある場合に true を返すメソッドです。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


この com.aspose.psd.RectangleF の com.aspose.psd.RectangleF.Width または com.aspose.psd.RectangleF.Height プロパティがゼロであるかどうかを示す値を取得します。

**Returns:**
boolean - この com.aspose.psd.RectangleF の com.aspose.psd.RectangleF.Width または com.aspose.psd.RectangleF.Height プロパティの値がゼロの場合は true を返し、そうでない場合は false を返します。
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


現在の矩形の値を掛け算して変換行列の垂直および水平スケール値を変換し、結果の値を持つ新しい [RectangleF](../../com.aspose.psd/rectanglef) インスタンスを返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| transformMatrix | double[] | レイヤーの変換行列です。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
### normalize() {#normalize--}
```
public void normalize()
```


矩形の幅と高さを正にし、左が右より小さく、上が下より小さくなるように正規化します。

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


この矩形の位置を指定された量だけ調整します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | 位置をオフセットする量。 |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


この矩形の位置を指定された量だけ調整します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | 位置を水平方向にオフセットする量。 |
| y | float | 位置を垂直方向にオフセットする量。 |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


/ 演算子を実装します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 矩形です。 |
| 区切り | float | 区切りです。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


2 つの com.aspose.psd.RectangleF 構造体が位置とサイズが等しいかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | 等価演算子の左側にある com.aspose.psd.RectangleF 構造体です。 |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | 等価演算子の右側にある com.aspose.psd.RectangleF 構造体です。 |

**Returns:**
boolean - 指定された 2 つの com.aspose.psd.RectangleF 構造体が com.aspose.psd.RectangleF.X、com.aspose.psd.RectangleF.Y、com.aspose.psd.RectangleF.Width、com.aspose.psd.RectangleF.Height プロパティすべてで等しい場合に true を返します。
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


2 つの com.aspose.psd.RectangleF 構造体が位置またはサイズが異なるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | 不等価演算子の左側にある com.aspose.psd.RectangleF 構造体です。 |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | 不等価演算子の右側にある com.aspose.psd.RectangleF 構造体です。 |

**Returns:**
boolean - 2 つの com.aspose.psd.RectangleF 構造体のいずれかの com.aspose.psd.RectangleF.X、com.aspose.psd.RectangleF.Y、com.aspose.psd.RectangleF.Width、または com.aspose.psd.RectangleF.Height プロパティが等しくない場合に true を返し、そうでない場合は false を返します。
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


\* 演算子を実装します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | 矩形です。 |
| 乗数 | float | 乗数です。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


この com.aspose.psd.RectangleF 構造体の com.aspose.psd.RectangleF.Y と com.aspose.psd.RectangleF.Height の合計である y 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


この com.aspose.psd.RectangleF 構造体の高さを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


この com.aspose.psd.RectangleF 構造体の左端の x 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


この com.aspose.psd.RectangleF 構造体の左上隅の座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


この com.aspose.psd.RectangleF 構造体の com.aspose.psd.RectangleF.X と com.aspose.psd.RectangleF.Width の合計である x 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


この com.aspose.psd.RectangleF のサイズを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


この com.aspose.psd.RectangleF 構造体の上端の y 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


この com.aspose.psd.RectangleF 構造体の幅を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


この com.aspose.psd.RectangleF 構造体の左上隅の x 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


この com.aspose.psd.RectangleF 構造体の左上隅の y 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


[RectangleF](../../com.aspose.psd/rectanglef) を切り捨てた矩形値を持つ [Rectangle](../../com.aspose.psd/rectangle) 構造体に変換します。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


この com.aspose.psd.RectangleF の属性を人間が読みやすい文字列に変換します。

**Returns:**
java.lang.String - この com.aspose.psd.RectangleF 構造体の位置、幅、高さを含む文字列です。
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


指定された  com.aspose.psd.Rectangle  構造体を  com.aspose.psd.RectangleF  構造体に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 変換する com.aspose.psd.Rectangle 構造体です。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


2つの矩形の合併を形成する両方を含むことができる、可能な限り最小の3番目の矩形を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | 結合する最初の矩形。 |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | 結合する2番目の矩形。 |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure that contains both of the two rectangles that form the union.
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

