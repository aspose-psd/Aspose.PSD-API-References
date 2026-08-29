---
title: "PointF"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "2 次元平面上の点を定義する、浮動小数点の x および y 座標の順序付きペアを表します。"
type: docs
weight: 83
url: /ja/java/com.aspose.psd/pointf/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

2 次元平面上の点を定義する、浮動小数点の x および y 座標の順序付きペアを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | 指定された座標で com.aspose.psd.PointF 構造体の新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(PointF that)](#CloneTo-com.aspose.psd.PointF-) |  |
| [add(PointF point, Size size)](#add-com.aspose.psd.PointF-com.aspose.psd.Size-) | 指定された com.aspose.psd.Size で、指定された com.aspose.psd.PointF を平行移動します。 |
| [add(PointF point, SizeF size)](#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | 指定された com.aspose.psd.SizeF で、指定された com.aspose.psd.PointF を平行移動します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | この com.aspose.psd.PointF が指定された System.Object と同じ座標を含むかどうかを指定します。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | com.aspose.psd.PointF.X と com.aspose.psd.PointF.Y の値がゼロに設定された com.aspose.psd.PointF 構造体の新しいインスタンスを取得します。 |
| [getX()](#getX--) | この com.aspose.psd.PointF の X 座標を取得または設定します。 |
| [getY()](#getY--) | この com.aspose.psd.PointF の Y 座標を取得または設定します。 |
| [hashCode()](#hashCode--) | この com.aspose.psd.PointF 構造体のハッシュコードを返します。 |
| [isEmpty()](#isEmpty--) | この com.aspose.psd.PointF が空かどうかを示す値を取得します。 |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-) | 指定された com.aspose.psd.Size で、com.aspose.psd.PointF を平行移動します。 |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | 指定された com.aspose.psd.SizeF で、com.aspose.psd.PointF を平行移動します。 |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | 2つの com.aspose.psd.PointF 構造体を比較します。 |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-) | 指定されたポイントの座標が等しくないかどうかを判定します。 |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-) | 指定された com.aspose.psd.Size の負の値で com.aspose.psd.PointF を平行移動します。 |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | 指定された com.aspose.psd.SizeF の負の値で com.aspose.psd.PointF を平行移動します。 |
| [setX(float value)](#setX-float-) | この com.aspose.psd.PointF の X 座標を取得または設定します。 |
| [setY(float value)](#setY-float-) | この com.aspose.psd.PointF の Y 座標を取得または設定します。 |
| [subtract(PointF point, Size size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-) | 指定されたサイズの負の値で com.aspose.psd.PointF を平行移動します。 |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | 指定されたサイズの負の値で com.aspose.psd.PointF を平行移動します。 |
| [toString()](#toString--) | この com.aspose.psd.PointF を人間が読みやすい文字列に変換します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


指定された座標で com.aspose.psd.PointF 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | float | ポイントの水平位置です。 |
| y | float | ポイントの垂直位置です。 |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.psd/pointf)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(PointF that) {#CloneTo-com.aspose.psd.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| that | [PointF](../../com.aspose.psd/pointf) |  |

### add(PointF point, Size size) {#add-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF add(PointF point, Size size)
```


指定された com.aspose.psd.Size で、指定された com.aspose.psd.PointF を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 平行移動する com.aspose.psd.PointF。 |
| size | [Size](../../com.aspose.psd/size) | ポイントの座標に加える数値を指定する com.aspose.psd.Size。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### add(PointF point, SizeF size) {#add-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


指定された com.aspose.psd.SizeF で、指定された com.aspose.psd.PointF を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 平行移動する com.aspose.psd.PointF。 |
| size | [SizeF](../../com.aspose.psd/sizef) | ポイントの座標に加える数値を指定する com.aspose.psd.SizeF。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


この com.aspose.psd.PointF が指定された System.Object と同じ座標を含むかどうかを指定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | テスト対象の  System.Object  です。 |

**Returns:**
boolean - このメソッドは、obj が com.aspose.psd.PointF であり、この com.aspose.psd.Point と同じ座標を持つ場合に true を返します。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


com.aspose.psd.PointF.X と com.aspose.psd.PointF.Y の値がゼロに設定された com.aspose.psd.PointF 構造体の新しいインスタンスを取得します。

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getX() {#getX--}
```
public float getX()
```


この com.aspose.psd.PointF の X 座標を取得または設定します。

**Returns:**
float
### getY() {#getY--}
```
public float getY()
```


この com.aspose.psd.PointF の Y 座標を取得または設定します。

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


この com.aspose.psd.PointF 構造体のハッシュコードを返します。

**Returns:**
int - この com.aspose.psd.PointF 構造体のハッシュ値を指定する整数です。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


この com.aspose.psd.PointF が空かどうかを示す値を取得します。

**Returns:**
boolean - com.aspose.psd.PointF.X と com.aspose.psd.PointF.Y の両方が 0 の場合は true、そうでない場合は false です。
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.psd/pointf) |  |
| obj2 | [PointF](../../com.aspose.psd/pointf) |  |

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




### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


指定された com.aspose.psd.Size で、com.aspose.psd.PointF を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 平行移動する com.aspose.psd.PointF。 |
| size | [Size](../../com.aspose.psd/size) | ポイントの座標に加える数値のペアを指定する com.aspose.psd.Size。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - Returns the translated  com.aspose.psd.PointF .
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


指定された com.aspose.psd.SizeF で、com.aspose.psd.PointF を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 平行移動する com.aspose.psd.PointF。 |
| size | [SizeF](../../com.aspose.psd/sizef) | ポイントの x および y 座標に加える数値を指定する com.aspose.psd.SizeF。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


2つの com.aspose.psd.PointF 構造体を比較します。結果は、2つの com.aspose.psd.PointF 構造体の com.aspose.psd.PointF.X と com.aspose.psd.PointF.Y プロパティの値が等しいかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | 比較対象となる最初の com.aspose.psd.PointF。 |
| point2 | [PointF](../../com.aspose.psd/pointf) | 比較対象となる2番目の com.aspose.psd.PointF。 |

**Returns:**
boolean - 最初と2番目の com.aspose.psd.PointF 構造体の com.aspose.psd.PointF.X と com.aspose.psd.PointF.Y の値が等しい場合は true、そうでない場合は false です。
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


指定されたポイントの座標が等しくないかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | 比較対象となる最初の com.aspose.psd.PointF。 |
| point2 | [PointF](../../com.aspose.psd/pointf) | 比較対象となる2番目の com.aspose.psd.PointF。 |

**Returns:**
boolean - point1 と point2 の com.aspose.psd.PointF.X と com.aspose.psd.PointF.Y の値が等しくないことを示す場合は true、そうでない場合は false です。
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


指定された com.aspose.psd.Size の負の値で com.aspose.psd.PointF を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 平行移動する com.aspose.psd.PointF。 |
| size | [Size](../../com.aspose.psd/size) | ポイントの x および y 座標から減算する数値を指定する com.aspose.psd.Size。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


指定された com.aspose.psd.SizeF の負の値で com.aspose.psd.PointF を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 平行移動する com.aspose.psd.PointF。 |
| size | [SizeF](../../com.aspose.psd/sizef) | ポイントの座標から減算する数値を指定する com.aspose.psd.SizeF。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


この com.aspose.psd.PointF の X 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


この com.aspose.psd.PointF の Y 座標を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### subtract(PointF point, Size size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.Size-}
```
public static PointF subtract(PointF point, Size size)
```


指定されたサイズの負の値で com.aspose.psd.PointF を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 平行移動する com.aspose.psd.PointF。 |
| size | [Size](../../com.aspose.psd/size) | ポイントの座標から減算する数値を指定する com.aspose.psd.Size。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### subtract(PointF point, SizeF size) {#subtract-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


指定されたサイズの負の値で com.aspose.psd.PointF を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | 平行移動する com.aspose.psd.PointF。 |
| size | [SizeF](../../com.aspose.psd/sizef) | ポイントの座標から減算する数値を指定する com.aspose.psd.SizeF。 |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The translated  com.aspose.psd.PointF .
### toString() {#toString--}
```
public String toString()
```


この com.aspose.psd.PointF を人間が読みやすい文字列に変換します。

**Returns:**
java.lang.String - この com.aspose.psd.PointF を表す文字列です。
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

