---
title: "Size"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "サイズを表します。"
type: docs
weight: 98
url: /ja/java/com.aspose.psd/size/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

サイズを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.psd.Point-) | 指定された Aspose.Imaging.Point から Aspose.Imaging.Size 構造体の新しいインスタンスを初期化します。 |
| [Size(int width, int height)](#Size-int-int-) | 指定された寸法から Aspose.Imaging.Size 構造体の新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Size that)](#CloneTo-com.aspose.psd.Size-) |  |
| [add(Size size1, Size size2)](#add-com.aspose.psd.Size-com.aspose.psd.Size-) | 1つの Aspose.Imaging.Size 構造体の幅と高さを、別の Aspose.Imaging.Size 構造体の幅と高さに加算します。 |
| [ceiling(SizeF size)](#ceiling-com.aspose.psd.SizeF-) | 指定された Aspose.Imaging.SizeF 構造体を、Aspose.Imaging.Size 構造体に変換します。変換時に Aspose.Imaging.Size の値を次の整数に切り上げます。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトが、この Aspose.Imaging.Size と同じ寸法の Aspose.Imaging.Size かどうかをテストします。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Aspose.Imaging.Size.Width と Aspose.Imaging.Size.Height の値が 0 に設定された、新しい Aspose.Imaging.Size 構造体のインスタンスを取得します。 |
| [getHeight()](#getHeight--) | この Aspose.Imaging.Size の垂直成分を取得または設定します。 |
| [getWidth()](#getWidth--) | この Aspose.Imaging.Size の水平成分を取得または設定します。 |
| [hashCode()](#hashCode--) | この Aspose.Imaging.Size 構造体のハッシュコードを返します。 |
| [isEmpty()](#isEmpty--) | この Aspose.Imaging.Size の幅と高さが 0 かどうかを示す値を取得します。 |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-) | 1つの Aspose.Imaging.Size 構造体の幅と高さを、別の Aspose.Imaging.Size 構造体の幅と高さに加算します。 |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-) | 2つの Aspose.Imaging.Size 構造体が等しいかどうかをテストします。 |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-) | 2つの Aspose.Imaging.Size 構造体が異なるかどうかをテストします。 |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-) | 1つの Aspose.Imaging.Size 構造体の幅と高さを、別の Aspose.Imaging.Size 構造体の幅と高さから減算します。 |
| [round(SizeF size)](#round-com.aspose.psd.SizeF-) | 指定された Aspose.Imaging.SizeF 構造体を、Aspose.Imaging.Size 構造体に変換します。変換時に Aspose.Imaging.SizeF の値を最も近い整数に丸めます。 |
| [setHeight(int value)](#setHeight-int-) | この Aspose.Imaging.Size の垂直成分を取得または設定します。 |
| [setWidth(int value)](#setWidth-int-) | この Aspose.Imaging.Size の水平成分を取得または設定します。 |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.psd.Size-com.aspose.psd.Size-) | 1つの Aspose.Imaging.Size 構造体の幅と高さを、別の Aspose.Imaging.Size 構造体の幅と高さから減算します。 |
| [toString()](#toString--) | この Aspose.Imaging.Size を表す、人間が読みやすい文字列を作成します。 |
| [to_Point(Size size)](#to-Point-com.aspose.psd.Size-) | 指定された Aspose.Imaging.Size を Aspose.Imaging.Point に変換します。 |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.psd.Size-) | 指定された Aspose.Imaging.Size を Aspose.Imaging.SizeF に変換します。 |
| [truncate(SizeF size)](#truncate-com.aspose.psd.SizeF-) | 指定された Aspose.Imaging.SizeF 構造体を、Aspose.Imaging.Size 構造体に変換します。変換時に Aspose.Imaging.SizeF の値を次の整数に切り捨てます。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.psd.Point-}
```
public Size(Point point)
```


指定された Aspose.Imaging.Point から Aspose.Imaging.Size 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | この Aspose.Imaging.Size を初期化する元となる Aspose.Imaging.Point。 |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


指定された寸法から Aspose.Imaging.Size 構造体の新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 | int | 新しい Aspose.Imaging.Size の幅成分。 |
| 高さ | int | 新しい Aspose.Imaging.Size の高さ成分。 |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.psd/size)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Size that) {#CloneTo-com.aspose.psd.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| that | [Size](../../com.aspose.psd/size) |  |

### add(Size size1, Size size2) {#add-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size add(Size size1, Size size2)
```


1つの Aspose.Imaging.Size 構造体の幅と高さを、別の Aspose.Imaging.Size 構造体の幅と高さに加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 加算する最初の Aspose.Imaging.Size。 |
| size2 | [Size](../../com.aspose.psd/size) | 加算する2番目の Aspose.Imaging.Size。 |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.psd.SizeF-}
```
public static Size ceiling(SizeF size)
```


指定された Aspose.Imaging.SizeF 構造体を、Aspose.Imaging.Size 構造体に変換します。変換時に Aspose.Imaging.Size の値を次の整数に切り上げます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 変換する Aspose.Imaging.SizeF 構造体。 |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトが、この Aspose.Imaging.Size と同じ寸法の Aspose.Imaging.Size かどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | テスト対象の  System.Object  です。 |

**Returns:**
boolean - obj が Aspose.Imaging.Size であり、この Aspose.Imaging.Size と同じ幅と高さを持つ場合は true、そうでない場合は false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Aspose.Imaging.Size.Width と Aspose.Imaging.Size.Height の値が 0 に設定された、新しい Aspose.Imaging.Size 構造体のインスタンスを取得します。

**Returns:**
[Size](../../com.aspose.psd/size)
### getHeight() {#getHeight--}
```
public int getHeight()
```


この Aspose.Imaging.Size の垂直成分を取得または設定します。

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


この Aspose.Imaging.Size の水平成分を取得または設定します。

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


この Aspose.Imaging.Size 構造体のハッシュコードを返します。

**Returns:**
int - この Aspose.Imaging.Size 構造体のハッシュ値を指定する整数値。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


この Aspose.Imaging.Size の幅と高さが 0 かどうかを示す値を取得します。

**Returns:**
boolean
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.psd/size) |  |
| obj2 | [Size](../../com.aspose.psd/size) |  |

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




### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


1つの Aspose.Imaging.Size 構造体の幅と高さを、別の Aspose.Imaging.Size 構造体の幅と高さに加算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 加算する最初の Aspose.Imaging.Size。 |
| size2 | [Size](../../com.aspose.psd/size) | 加算する2番目の Aspose.Imaging.Size。 |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the addition operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


2つの Aspose.Imaging.Size 構造体が等しいかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 等価演算子の左側にある Aspose.Imaging.Size 構造体。 |
| size2 | [Size](../../com.aspose.psd/size) | 等価演算子の右側にある Aspose.Imaging.Size 構造体。 |

**Returns:**
boolean - size1 と size2 の幅と高さが等しい場合は true、そうでない場合は false。
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


2つの Aspose.Imaging.Size 構造体が異なるかどうかをテストします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 不等号演算子の左側にある Aspose.Imaging.Size 構造体。 |
| size2 | [Size](../../com.aspose.psd/size) | 不等号演算子の右側にある Aspose.Imaging.Size 構造体。 |

**Returns:**
boolean - size1 と size2 の幅または高さのいずれかが異なる場合は true、size1 と size2 が等しい場合は false。
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


1つの Aspose.Imaging.Size 構造体の幅と高さを、別の Aspose.Imaging.Size 構造体の幅と高さから減算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 減算演算子の左側にある Aspose.Imaging.Size 構造体。 |
| size2 | [Size](../../com.aspose.psd/size) | 減算演算子の右側にある Aspose.Imaging.Size 構造体。 |

**Returns:**
[Size](../../com.aspose.psd/size) - A  Aspose.Imaging.Size  structure that is the result of the subtraction operation.
### round(SizeF size) {#round-com.aspose.psd.SizeF-}
```
public static Size round(SizeF size)
```


指定された Aspose.Imaging.SizeF 構造体を、Aspose.Imaging.Size 構造体に変換します。変換時に Aspose.Imaging.SizeF の値を最も近い整数に丸めます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 変換する Aspose.Imaging.SizeF 構造体。 |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


この Aspose.Imaging.Size の垂直成分を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


この Aspose.Imaging.Size の水平成分を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### subtract(Size size1, Size size2) {#subtract-com.aspose.psd.Size-com.aspose.psd.Size-}
```
public static Size subtract(Size size1, Size size2)
```


1つの Aspose.Imaging.Size 構造体の幅と高さを、別の Aspose.Imaging.Size 構造体の幅と高さから減算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.psd/size) | 減算演算子の左側にある Aspose.Imaging.Size 構造体。 |
| size2 | [Size](../../com.aspose.psd/size) | 減算演算子の右側にある Aspose.Imaging.Size 構造体。 |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that is a result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


この Aspose.Imaging.Size を表す、人間が読みやすい文字列を作成します。

**Returns:**
java.lang.String - この Aspose.Imaging.Size を表す文字列。
### to_Point(Size size) {#to-Point-com.aspose.psd.Size-}
```
public static Point to_Point(Size size)
```


指定された Aspose.Imaging.Size を Aspose.Imaging.Point に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | 変換する Aspose.Imaging.Size。 |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  structure to which this operator converts.
### to_SizeF(Size size) {#to-SizeF-com.aspose.psd.Size-}
```
public static SizeF to_SizeF(Size size)
```


指定された Aspose.Imaging.Size を Aspose.Imaging.SizeF に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | 変換する Aspose.Imaging.Size。 |

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - The  Aspose.Imaging.SizeF  structure to which this operator converts.
### truncate(SizeF size) {#truncate-com.aspose.psd.SizeF-}
```
public static Size truncate(SizeF size)
```


指定された Aspose.Imaging.SizeF 構造体を、Aspose.Imaging.Size 構造体に変換します。変換時に Aspose.Imaging.SizeF の値を次の整数に切り捨てます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | 変換する Aspose.Imaging.SizeF 構造体。 |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  structure this method converts to.
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

