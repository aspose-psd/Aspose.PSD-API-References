---
title: "Rectangle"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "矩形の位置とサイズを表す 4 つの整数のセットを格納します。"
type: docs
weight: 88
url: /ja/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

矩形の位置とサイズを表す 4 つの整数のセットを格納します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | 指定された位置とサイズで com.aspose.psd.Rectangle 構造体の新しいインスタンスを初期化します。 |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | 指定された位置とサイズで com.aspose.psd.Rectangle 構造体の新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | 指定された com.aspose.psd.RectangleF 構造体を、値を次の整数に切り上げて com.aspose.psd.Rectangle 構造体に変換します。 |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | 指定された点がこの com.aspose.psd.Rectangle 構造体に含まれているかどうかを判断します。 |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | rect が表す矩形領域がこの com.aspose.psd.Rectangle 構造体に完全に含まれているかどうかを判断します。 |
| [contains(int x, int y)](#contains-int-int-) | 指定された点がこの com.aspose.psd.Rectangle 構造体に含まれているかどうかを判断します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | obj がこの com.aspose.psd.Rectangle 構造体と同じ位置とサイズを持つ com.aspose.psd.Rectangle 構造体かどうかをテストします。 |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | 指定されたエッジ位置で com.aspose.psd.Rectangle 構造体を作成します。 |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | 指定された2点から新しい Rectangle を作成します。 |
| [getBottom()](#getBottom--) | この com.aspose.psd.Rectangle 構造体の com.aspose.psd.Rectangle.Y と com.aspose.psd.Rectangle.Height プロパティ値の合計である y 座標を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | com.aspose.psd.Rectangle.X、com.aspose.psd.Rectangle.Y、com.aspose.psd.Rectangle.Width、com.aspose.psd.Rectangle.Height の値がすべてゼロに設定された com.aspose.psd.Rectangle 構造体の新しいインスタンスを取得します。 |
| [getHeight()](#getHeight--) | この com.aspose.psd.Rectangle 構造体の高さを取得または設定します。 |
| [getLeft()](#getLeft--) | この com.aspose.psd.Rectangle 構造体の左端の x 座標を取得または設定します。 |
| [getLocation()](#getLocation--) | この com.aspose.psd.Rectangle 構造体の左上隅の座標を取得または設定します。 |
| [getRight()](#getRight--) | この com.aspose.psd.Rectangle 構造体の com.aspose.psd.Rectangle.X と com.aspose.psd.Rectangle.Width プロパティ値の合計である x 座標を取得または設定します。 |
| [getSize()](#getSize--) | この com.aspose.psd.Rectangle のサイズを取得または設定します。 |
| [getTop()](#getTop--) | この com.aspose.psd.Rectangle 構造体の上端の y 座標を取得または設定します。 |
| [getWidth()](#getWidth--) | この com.aspose.psd.Rectangle 構造体の幅を取得します。 |
| [getX()](#getX--) | この com.aspose.psd.Rectangle 構造体の左上隅の x 座標を取得または設定します。 |
| [getY()](#getY--) | この com.aspose.psd.Rectangle 構造体の左上隅の y 座標を取得または設定します。 |
| [hashCode()](#hashCode--) | この com.aspose.psd.Rectangle 構造体のハッシュコードを返します。 |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | 指定された com.aspose.psd.Rectangle 構造体の拡張コピーを作成して返します。 |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | この com.aspose.psd.Rectangle を指定された量だけ拡張します。 |
| [inflate(int width, int height)](#inflate-int-int-) | この com.aspose.psd.Rectangle を指定された量だけ拡張します。 |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | この com.aspose.psd.Rectangle を自身と指定された com.aspose.psd.Rectangle の交差部分に置き換えます。 |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 他の 2 つの com.aspose.psd.Rectangle 構造体の交差を表す 3 番目の com.aspose.psd.Rectangle 構造体を返します。 |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | この矩形が rect と交差するかどうかを判定します。 |
| [isEmpty()](#isEmpty--) | この com.aspose.psd.Rectangle のすべての数値プロパティがゼロであるかどうかを示す値を取得します。 |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | この  Rectangle  が少なくとも部分的に表示されているかどうかを示す値を取得します。 |
| [normalize()](#normalize--) | 矩形の幅と高さを正にし、左が右より小さく、上が下より小さくなるように正規化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | この矩形の位置を指定された量だけ調整します。 |
| [offset(int x, int y)](#offset-int-int-) | この矩形の位置を指定された量だけ調整します。 |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 2つの com.aspose.psd.Rectangle 構造体が位置とサイズが等しいかどうかをテストします。 |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 2つの com.aspose.psd.Rectangle 構造体が位置またはサイズが異なるかどうかをテストします。 |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | 指定された com.aspose.psd.RectangleF を、com.aspose.psd.RectangleF の値を最も近い整数に丸めて com.aspose.psd.Rectangle に変換します。 |
| [setBottom(int value)](#setBottom-int-) | この com.aspose.psd.Rectangle 構造体の com.aspose.psd.Rectangle.Y と com.aspose.psd.Rectangle.Height プロパティ値の合計である y 座標を取得または設定します。 |
| [setHeight(int value)](#setHeight-int-) | この com.aspose.psd.Rectangle 構造体の高さを取得または設定します。 |
| [setLeft(int value)](#setLeft-int-) | この com.aspose.psd.Rectangle 構造体の左端の x 座標を取得または設定します。 |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | この com.aspose.psd.Rectangle 構造体の左上隅の座標を取得または設定します。 |
| [setRight(int value)](#setRight-int-) | この com.aspose.psd.Rectangle 構造体の com.aspose.psd.Rectangle.X と com.aspose.psd.Rectangle.Width プロパティ値の合計である x 座標を取得または設定します。 |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | この com.aspose.psd.Rectangle のサイズを取得または設定します。 |
| [setTop(int value)](#setTop-int-) | この com.aspose.psd.Rectangle 構造体の上端の y 座標を取得または設定します。 |
| [setWidth(int value)](#setWidth-int-) | この com.aspose.psd.Rectangle 構造体の幅を設定します。 |
| [setX(int value)](#setX-int-) | この com.aspose.psd.Rectangle 構造体の左上隅の x 座標を取得または設定します。 |
| [setY(int value)](#setY-int-) | この com.aspose.psd.Rectangle 構造体の左上隅の y 座標を取得または設定します。 |
| [toString()](#toString--) | この com.aspose.psd.Rectangle の属性を人間が読みやすい文字列に変換します。 |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | 指定された com.aspose.psd.RectangleF を、com.aspose.psd.RectangleF の値を切り捨てて com.aspose.psd.Rectangle に変換します。 |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | 2つの com.aspose.psd.Rectangle 構造体の合併を含む com.aspose.psd.Rectangle 構造体を取得します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


指定された位置とサイズで com.aspose.psd.Rectangle 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | 矩形の左上隅の x 座標です。 |
| y | int | 矩形の左上隅の y 座標です。 |
| 幅 | int | 矩形の幅です。 |
| 高さ | int | 矩形の高さです。 |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


指定された位置とサイズで com.aspose.psd.Rectangle 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | 矩形領域の左上隅を表す com.aspose.psd.Point。 |
| size | [Size](../../com.aspose.psd/size) | 矩形領域の幅と高さを表す com.aspose.psd.Size。 |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


指定された com.aspose.psd.RectangleF 構造体を、値を次の整数に切り上げて com.aspose.psd.Rectangle 構造体に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | 変換対象の com.aspose.psd.RectangleF 構造体。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


指定された点がこの com.aspose.psd.Rectangle 構造体に含まれているかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | テスト対象の com.aspose.psd.Point。 |

**Returns:**
boolean - このメソッドは、point がこの com.aspose.psd.Rectangle 構造体内に含まれている場合に true を返し、そうでない場合は false を返します。
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


rect が表す矩形領域がこの com.aspose.psd.Rectangle 構造体に完全に含まれているかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | テスト対象の com.aspose.psd.Rectangle。 |

**Returns:**
boolean - このメソッドは、rect が表す矩形領域がこの com.aspose.psd.Rectangle 構造体に完全に含まれている場合に true を返し、そうでない場合は false を返します。
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


指定された点がこの com.aspose.psd.Rectangle 構造体に含まれているかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | テスト対象の点の x 座標です。 |
| y | int | テスト対象の点の y 座標です。 |

**Returns:**
boolean - このメソッドは、x と y で定義された点がこの com.aspose.psd.Rectangle 構造体内に含まれている場合に true を返し、そうでない場合は false を返します。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


obj がこの com.aspose.psd.Rectangle 構造体と同じ位置とサイズを持つ com.aspose.psd.Rectangle 構造体かどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | テスト対象の  System.Object  です。 |

**Returns:**
boolean - このメソッドは、obj が com.aspose.psd.Rectangle 構造体であり、その com.aspose.psd.Rectangle.X、com.aspose.psd.Rectangle.Y、com.aspose.psd.Rectangle.Width、com.aspose.psd.Rectangle.Height プロパティがこの com.aspose.psd.Rectangle 構造体の対応するプロパティと等しい場合に true を返し、そうでない場合は false を返します。
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


指定されたエッジ位置で com.aspose.psd.Rectangle 構造体を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | int | この com.aspose.psd.Rectangle 構造体の左上隅の x 座標。 |
| top | int | この com.aspose.psd.Rectangle 構造体の左上隅の y 座標。 |
| right | int | この com.aspose.psd.Rectangle 構造体の右下隅の x 座標。 |
| 下 | int | この com.aspose.psd.Rectangle 構造体の右下隅の y 座標。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


指定された2つの点から新しい Rectangle を作成します。作成された Rectangle の2つの垂直辺は、渡された point1 と point2 に等しくなります。これらは通常、対角の頂点です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | 新しい矩形の最初の Point です。 |
| point2 | [Point](../../com.aspose.psd/point) | 新しい矩形の2番目の Point です。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


この com.aspose.psd.Rectangle 構造体の com.aspose.psd.Rectangle.Y と com.aspose.psd.Rectangle.Height プロパティ値の合計である y 座標を取得または設定します。

**Returns:**
int - この com.aspose.psd.Rectangle の com.aspose.psd.Rectangle.Y と com.aspose.psd.Rectangle.Height の合計である y 座標。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


com.aspose.psd.Rectangle.X、com.aspose.psd.Rectangle.Y、com.aspose.psd.Rectangle.Width、com.aspose.psd.Rectangle.Height の値がすべてゼロに設定された com.aspose.psd.Rectangle 構造体の新しいインスタンスを取得します。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


この com.aspose.psd.Rectangle 構造体の高さを取得または設定します。

**Returns:**
int - この com.aspose.psd.Rectangle 構造体の高さ。
### getLeft() {#getLeft--}
```
public int getLeft()
```


この com.aspose.psd.Rectangle 構造体の左端の x 座標を取得または設定します。

**Returns:**
int - この com.aspose.psd.Rectangle 構造体の左端の x 座標。
### getLocation() {#getLocation--}
```
public Point getLocation()
```


この com.aspose.psd.Rectangle 構造体の左上隅の座標を取得または設定します。

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


この com.aspose.psd.Rectangle 構造体の com.aspose.psd.Rectangle.X と com.aspose.psd.Rectangle.Width プロパティ値の合計である x 座標を取得または設定します。

**Returns:**
int - この com.aspose.psd.Rectangle の com.aspose.psd.Rectangle.X と com.aspose.psd.Rectangle.Width の合計である x 座標です。
### getSize() {#getSize--}
```
public Size getSize()
```


この com.aspose.psd.Rectangle のサイズを取得または設定します。

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


この com.aspose.psd.Rectangle 構造体の上端の y 座標を取得または設定します。

**Returns:**
int - この com.aspose.psd.Rectangle 構造体の上端の y 座標です。
### getWidth() {#getWidth--}
```
public int getWidth()
```


この com.aspose.psd.Rectangle 構造体の幅を取得します。

**Returns:**
int - この com.aspose.psd.Rectangle 構造体の幅です。
### getX() {#getX--}
```
public int getX()
```


この com.aspose.psd.Rectangle 構造体の左上隅の x 座標を取得または設定します。

**Returns:**
int - この com.aspose.psd.Rectangle 構造体の左上隅の x 座標です。
### getY() {#getY--}
```
public int getY()
```


この com.aspose.psd.Rectangle 構造体の左上隅の y 座標を取得または設定します。

**Returns:**
int - この com.aspose.psd.Rectangle 構造体の左上隅の y 座標です。
### hashCode() {#hashCode--}
```
public int hashCode()
```


この com.aspose.psd.Rectangle 構造体のハッシュコードを返します。

**Returns:**
int - この矩形のハッシュコードを表す整数です。
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


指定された com.aspose.psd.Rectangle 構造体の拡張コピーを作成して返します。コピーは指定された量だけ拡張されます。元の com.aspose.psd.Rectangle 構造体は変更されません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 開始に使用する com.aspose.psd.Rectangle です。この矩形は変更されません。 |
| x | int | この com.aspose.psd.Rectangle を水平方向に拡張する量です。 |
| y | int | この com.aspose.psd.Rectangle を垂直方向に拡張する量です。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


この com.aspose.psd.Rectangle を指定された量だけ拡張します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | この矩形を拡張する量です。 |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


この com.aspose.psd.Rectangle を指定された量だけ拡張します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 | int | この com.aspose.psd.Rectangle を水平方向に拡張する量です。 |
| 高さ | int | この com.aspose.psd.Rectangle を垂直方向に拡張する量です。 |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


この com.aspose.psd.Rectangle を自身と指定された com.aspose.psd.Rectangle の交差部分に置き換えます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 交差させるための com.aspose.psd.Rectangle です。 |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


2 つの別の com.aspose.psd.Rectangle 構造体の交差を表す 3 番目の com.aspose.psd.Rectangle 構造体を返します。交差がない場合は空の com.aspose.psd.Rectangle が返されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | 交差させる最初の矩形です。 |
| b | [Rectangle](../../com.aspose.psd/rectangle) | 交差させる2番目の矩形です。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


この矩形が rect と交差するかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | テストする矩形。 |

**Returns:**
boolean - 交差がある場合は true を、そうでない場合は false を返すメソッドです。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


この com.aspose.psd.Rectangle のすべての数値プロパティがゼロであるかどうかを示す値を取得します。

**Returns:**
boolean - この com.aspose.psd.Rectangle の com.aspose.psd.Rectangle.Width、com.aspose.psd.Rectangle.Height、com.aspose.psd.Rectangle.X、com.aspose.psd.Rectangle.Y プロパティがすべて 0 の場合に true を返し、そうでない場合は false を返すプロパティです。
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


この  Rectangle  が少なくとも部分的に表示されているかどうかを示す値を取得します。

**Returns:**
boolean - この Rectangle が少なくとも部分的に表示されている場合は true、そうでない場合は false です。
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




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


この矩形の位置を指定された量だけ調整します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | 位置をオフセットする量です。 |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


この矩形の位置を指定された量だけ調整します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | 水平オフセットです。 |
| y | int | 垂直オフセットです。 |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


2つの com.aspose.psd.Rectangle 構造体が位置とサイズが等しいかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | 等価演算子の左側にある com.aspose.psd.Rectangle 構造体です。 |
| right | [Rectangle](../../com.aspose.psd/rectangle) | 等価演算子の右側にある com.aspose.psd.Rectangle 構造体です。 |

**Returns:**
boolean - 2 つの com.aspose.psd.Rectangle 構造体が com.aspose.psd.Rectangle.X、com.aspose.psd.Rectangle.Y、com.aspose.psd.Rectangle.Width、com.aspose.psd.Rectangle.Height プロパティで等しい場合に true を返す演算子です。
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


2つの com.aspose.psd.Rectangle 構造体が位置またはサイズが異なるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | 不等価演算子の左側にある com.aspose.psd.Rectangle 構造体です。 |
| right | [Rectangle](../../com.aspose.psd/rectangle) | 不等価演算子の右側にある com.aspose.psd.Rectangle 構造体です。 |

**Returns:**
boolean - 2 つの com.aspose.psd.Rectangle 構造体の com.aspose.psd.Rectangle.X、com.aspose.psd.Rectangle.Y、com.aspose.psd.Rectangle.Width、または com.aspose.psd.Rectangle.Height プロパティのいずれかが等しくない場合に true を返し、そうでない場合は false を返す演算子です。
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


指定された com.aspose.psd.RectangleF を、com.aspose.psd.RectangleF の値を最も近い整数に丸めて com.aspose.psd.Rectangle に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | 変換対象の com.aspose.psd.RectangleF です。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


この com.aspose.psd.Rectangle 構造体の com.aspose.psd.Rectangle.Y と com.aspose.psd.Rectangle.Height プロパティ値の合計である y 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この  com.aspose.psd.Rectangle の y 座標は、  com.aspose.psd.Rectangle.Y  と  com.aspose.psd.Rectangle.Height  の合計です。 |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


この com.aspose.psd.Rectangle 構造体の高さを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この  com.aspose.psd.Rectangle  構造体の高さです。 |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


この com.aspose.psd.Rectangle 構造体の左端の x 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この  com.aspose.psd.Rectangle  構造体の左端の x 座標です。 |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


この com.aspose.psd.Rectangle 構造体の左上隅の座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | この  com.aspose.psd.Rectangle  構造体の左上隅を表す  Point  です。 |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


この com.aspose.psd.Rectangle 構造体の com.aspose.psd.Rectangle.X と com.aspose.psd.Rectangle.Width プロパティ値の合計である x 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この  com.aspose.psd.Rectangle の x 座標は、  com.aspose.psd.Rectangle.X  と  com.aspose.psd.Rectangle.Width  の合計です。 |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


この com.aspose.psd.Rectangle のサイズを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | この  com.aspose.psd.Rectangle  構造体の幅と高さを表す  com.aspose.psd.Size  です。 |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


この com.aspose.psd.Rectangle 構造体の上端の y 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この  com.aspose.psd.Rectangle  構造体の上端の y 座標です。 |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


この com.aspose.psd.Rectangle 構造体の幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この  com.aspose.psd.Rectangle  構造体の幅です。 |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


この com.aspose.psd.Rectangle 構造体の左上隅の x 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この com.aspose.psd.Rectangle 構造体の左上隅の x 座標。 |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


この com.aspose.psd.Rectangle 構造体の左上隅の y 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この com.aspose.psd.Rectangle 構造体の左上隅の y 座標。 |

### toString() {#toString--}
```
public String toString()
```


この com.aspose.psd.Rectangle の属性を人間が読みやすい文字列に変換します。

**Returns:**
java.lang.String - この  com.aspose.psd.Rectangle  構造体の位置、幅、高さを含む文字列です。
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


指定された com.aspose.psd.RectangleF を、com.aspose.psd.RectangleF の値を切り捨てて com.aspose.psd.Rectangle に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | 変換対象の com.aspose.psd.RectangleF です。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


2つの com.aspose.psd.Rectangle 構造体の合併を含む com.aspose.psd.Rectangle 構造体を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | 結合する最初の矩形。 |
| b | [Rectangle](../../com.aspose.psd/rectangle) | 結合する2番目の矩形。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
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

