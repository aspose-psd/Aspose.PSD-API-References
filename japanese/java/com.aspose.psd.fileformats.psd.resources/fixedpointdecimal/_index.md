---
title: "FixedPointDecimal"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "16 ビット整数と 16 ビット小数部を持つ固定小数点数。"
type: docs
weight: 17
url: /ja/java/com.aspose.psd.fileformats.psd.resources/fixedpointdecimal/
---

**Inheritance:**
java.lang.Object
```
public class FixedPointDecimal
```

固定小数点数（16 ビット整数部と 16 ビット小数部）です。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [FixedPointDecimal(int integer, int fraction)](#FixedPointDecimal-int-int-) | 新しい [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) クラスのインスタンスを初期化します。 |
| [FixedPointDecimal(long value)](#FixedPointDecimal-long-) | 新しい [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) クラスのインスタンスを初期化します。 |
| [FixedPointDecimal(double value)](#FixedPointDecimal-double-) | 新しい [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFraction()](#getFraction--) | 小数部を取得または設定します。 |
| [getInteger()](#getInteger--) | 整数部を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFraction(int value)](#setFraction-int-) | 小数部を取得または設定します。 |
| [setInteger(int value)](#setInteger-int-) | 整数部を取得または設定します。 |
| [toDouble()](#toDouble--) | 現在の固定小数点数を double に変換します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FixedPointDecimal(int integer, int fraction) {#FixedPointDecimal-int-int-}
```
public FixedPointDecimal(int integer, int fraction)
```


新しい [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 整数 | int | 整数。 |
| 小数部 | int | 小数部。 |

### FixedPointDecimal(long value) {#FixedPointDecimal-long-}
```
public FixedPointDecimal(long value)
```


新しい [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) クラスのインスタンスを初期化します。32 ビット整数の上位語と下位語を分割して固定小数点数にします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long | 値です。 |

### FixedPointDecimal(double value) {#FixedPointDecimal-double-}
```
public FixedPointDecimal(double value)
```


新しい [FixedPointDecimal](../../com.aspose.psd.fileformats.psd.resources/fixedpointdecimal) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | 値です。 |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFraction() {#getFraction--}
```
public final int getFraction()
```


小数部を取得または設定します。

値: 小数部。

**Returns:**
int
### getInteger() {#getInteger--}
```
public final int getInteger()
```


整数部を取得または設定します。

値: 整数。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFraction(int value) {#setFraction-int-}
```
public final void setFraction(int value)
```


小数部を取得または設定します。

値: 小数部。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setInteger(int value) {#setInteger-int-}
```
public final void setInteger(int value)
```


整数部を取得または設定します。

値: 整数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```


現在の固定小数点数を double に変換します。

**Returns:**
double - 変換された値。
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

