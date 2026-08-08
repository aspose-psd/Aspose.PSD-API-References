---
title: "Point"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "2 次元平面上の点を定義する整数の x および y 座標の順序付きペアを表します。"
type: docs
weight: 82
url: /ja/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

2 次元平面上の点を定義する整数の x および y 座標の順序付きペアを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | 指定された座標で Aspose.Imaging.Point 構造体の新しいインスタンスを初期化します。 |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Aspose.Imaging.Size 構造体から Aspose.Imaging.Point 構造体の新しいインスタンスを初期化します。 |
| [Point(int dw)](#Point-int-) | 整数値で指定された座標を使用して Aspose.Imaging.Point 構造体の新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | ポイント形式を表します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | 指定された Aspose.Imaging.Size を指定された Aspose.Imaging.Point に加算します。 |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | 指定された Aspose.Imaging.PointF の値を次の整数に切り上げて、Aspose.Imaging.Point に変換します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | この Aspose.Imaging.Point が指定された System.Object と同じ座標を含むかどうかを指定します。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Aspose.Imaging.Point.X と Aspose.Imaging.Point.Y の値がゼロに設定された Aspose.Imaging.Point 構造体の新しいインスタンスを取得します。 |
| [getX()](#getX--) | この Aspose.Imaging.Point の X 座標を取得または設定します。 |
| [getY()](#getY--) | この Aspose.Imaging.Point の Y 座標を取得または設定します。 |
| [hashCode()](#hashCode--) | この Aspose.Imaging.Point のハッシュコードを返します。 |
| [isEmpty()](#isEmpty--) | この Aspose.Imaging.Point が空かどうかを示す値を取得します。 |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | この Aspose.Imaging.Point を指定された Aspose.Imaging.Point で平行移動します。 |
| [offset(int dx, int dy)](#offset-int-int-) | この Aspose.Imaging.Point を指定された量だけ平行移動します。 |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | Aspose.Imaging.Point を指定された Aspose.Imaging.Size だけ平行移動します。 |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | 2 つの Aspose.Imaging.Point オブジェクトを比較します。 |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | 2 つの Aspose.Imaging.Point オブジェクトを比較します。 |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | Aspose.Imaging.Point を指定された Aspose.Imaging.Size の負の値で平行移動します。 |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | 指定された Aspose.Imaging.PointF を、Aspose.Imaging.Point の値を最も近い整数に丸めて Aspose.Imaging.Point オブジェクトに変換します。 |
| [setX(int value)](#setX-int-) | この Aspose.Imaging.Point の X 座標を取得または設定します。 |
| [setY(int value)](#setY-int-) | この Aspose.Imaging.Point の Y 座標を取得または設定します。 |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | 指定された Aspose.Imaging.Point から指定された Aspose.Imaging.Size を減算した結果を返します。 |
| [toString()](#toString--) | この Aspose.Imaging.Point を人間が読みやすい文字列に変換します。 |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | 指定された Point 構造体を PointF 構造体に変換します。 |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | 指定された Aspose.Imaging.Point 構造体を Aspose.Imaging.Size 構造体に変換します。 |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | 指定された Aspose.Imaging.PointF を、Aspose.Imaging.Point の値を切り捨てて Aspose.Imaging.Point に変換します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


指定された座標で Aspose.Imaging.Point 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | int | ポイントの水平位置です。 |
| y | int | ポイントの垂直位置です。 |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Aspose.Imaging.Size 構造体から Aspose.Imaging.Point 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | 新しいポイント座標を含みます。 |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


整数値で指定された座標を使用して Aspose.Imaging.Point 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dw | int | 新しいポイントの座標を指定する 32 ビット整数です。 |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


ポイント形式を表します。

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


指定された Aspose.Imaging.Size を指定された Aspose.Imaging.Point に加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 追加先の Aspose.Imaging.Point です。 |
| size | [Size](../../com.aspose.psd/size) | ポイントに加える Aspose.Imaging.Size です。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


指定された Aspose.Imaging.PointF の値を次の整数に切り上げて、Aspose.Imaging.Point に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 変換する Aspose.Imaging.PointF です。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


この Aspose.Imaging.Point が指定された System.Object と同じ座標を含むかどうかを指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | テスト対象の  System.Object  です。 |

**Returns:**
boolean - obj が Aspose.Imaging.Point であり、この Aspose.Imaging.Point と同じ座標を持つ場合は True です。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Aspose.Imaging.Point.X と Aspose.Imaging.Point.Y の値がゼロに設定された Aspose.Imaging.Point 構造体の新しいインスタンスを取得します。

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


この Aspose.Imaging.Point の X 座標を取得または設定します。

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


この Aspose.Imaging.Point の Y 座標を取得または設定します。

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


この Aspose.Imaging.Point のハッシュコードを返します。

**Returns:**
int - このインスタンスのハッシュコード。ハッシュアルゴリズムやハッシュテーブルのようなデータ構造での使用に適しています。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


この Aspose.Imaging.Point が空かどうかを示す値を取得します。

**Returns:**
boolean - Aspose.Imaging.Point.X と Aspose.Imaging.Point.Y の両方が 0 の場合は True、そうでない場合は false です。
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


この Aspose.Imaging.Point を指定された Aspose.Imaging.Point で平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | この Aspose.Imaging.Point をオフセットするために使用される Aspose.Imaging.Point です。 |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


この Aspose.Imaging.Point を指定された量だけ平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | int | X 座標をオフセットする量です。 |
| dy | int | Y 座標をオフセットする量です。 |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Aspose.Imaging.Point を指定された Aspose.Imaging.Size だけ平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 平行移動する Aspose.Imaging.Point です。 |
| size | [Size](../../com.aspose.psd/size) | ポイントの座標に加える数のペアを指定する Aspose.Imaging.Size です。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


2 つの Aspose.Imaging.Point オブジェクトを比較します。結果は、2 つの Aspose.Imaging.Point オブジェクトの Aspose.Imaging.Point.X および Aspose.Imaging.Point.Y プロパティの値が等しいかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | 比較する最初の Aspose.Imaging.Point です。 |
| point2 | [Point](../../com.aspose.psd/point) | 比較する2番目の Aspose.Imaging.Point です。 |

**Returns:**
boolean - point1 と point2 の Aspose.Imaging.Point.X と Aspose.Imaging.Point.Y の値が等しい場合は True、そうでない場合は false です。
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


2 つの Aspose.Imaging.Point オブジェクトを比較します。結果は、2 つの Aspose.Imaging.Point オブジェクトの Aspose.Imaging.Point.X または Aspose.Imaging.Point.Y プロパティの値が等しくないかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | 比較する最初の Aspose.Imaging.Point です。 |
| point2 | [Point](../../com.aspose.psd/point) | 比較する2番目の Aspose.Imaging.Point です。 |

**Returns:**
boolean - point1 と point2 の Aspose.Imaging.Point.X プロパティまたは Aspose.Imaging.Point.Y プロパティのいずれかの値が異なる場合は True、そうでない場合は false です。
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Aspose.Imaging.Point を指定された Aspose.Imaging.Size の負の値で平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 平行移動する Aspose.Imaging.Point です。 |
| size | [Size](../../com.aspose.psd/size) | ポイントの座標から減算する数のペアを指定する Aspose.Imaging.Size です。 |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


指定された Aspose.Imaging.PointF を、Aspose.Imaging.Point の値を最も近い整数に丸めて Aspose.Imaging.Point オブジェクトに変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 変換する Aspose.Imaging.PointF です。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


この Aspose.Imaging.Point の X 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


この Aspose.Imaging.Point の Y 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


指定された Aspose.Imaging.Point から指定された Aspose.Imaging.Size を減算した結果を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 減算される側の Aspose.Imaging.Point です。 |
| size | [Size](../../com.aspose.psd/size) | ポイントから減算する Aspose.Imaging.Size です。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


この Aspose.Imaging.Point を人間が読みやすい文字列に変換します。

**Returns:**
java.lang.String - このインスタンスを表す System.String。
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


指定された Point 構造体を PointF 構造体に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 変換される Point です。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


指定された Aspose.Imaging.Point 構造体を Aspose.Imaging.Size 構造体に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | 変換される Aspose.Imaging.Point です。 |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


指定された Aspose.Imaging.PointF を、Aspose.Imaging.Point の値を切り捨てて Aspose.Imaging.Point に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 変換する Aspose.Imaging.PointF です。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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

