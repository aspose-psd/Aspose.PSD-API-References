---
title: "TiffRational"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "TIFF ラショナル型。"
type: docs
weight: 12
url: /ja/java/com.aspose.psd.fileformats.tiff/tiffrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffRational
```

TIFF ラショナル型。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [TiffRational()](#TiffRational--) | 新しいインスタンスとして  TiffRational  クラスを初期化します。 |
| [TiffRational(long value)](#TiffRational-long-) | 新しいインスタンスとして  TiffRational  クラスを初期化します。 |
| [TiffRational(long nominator, long denominator)](#TiffRational-long-long-) | 新しいインスタンスとして  TiffRational  クラスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Epsilon](#Epsilon) | 分数計算のイプシロン |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | 提供された値を分数に近似します。 |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | 提供された値を分数に近似します。 |
| [approximateFraction(float value)](#approximateFraction-float-) | 提供された値を分数に近似します。 |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | 提供された値を分数に近似します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトがこのインスタンスと等しいかどうかを判断します。 |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | 分母を取得します。 |
| [getNominator()](#getNominator--) | 分子を取得します。 |
| [getValue()](#getValue--) | 浮動小数点値を取得します。 |
| [getValueD()](#getValueD--) | double 値を取得します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | このインスタンスを表す  System.String  を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffRational() {#TiffRational--}
```
public TiffRational()
```


新しいインスタンスとして  TiffRational  クラスを初期化します。

### TiffRational(long value) {#TiffRational-long-}
```
public TiffRational(long value)
```


新しいインスタンスとして  TiffRational  クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | long | 分子の値。 |

分子は指定された値として使用され、分母は 1 になります。 |

### TiffRational(long nominator, long denominator) {#TiffRational-long-long-}
```
public TiffRational(long nominator, long denominator)
```


新しいインスタンスとして  TiffRational  クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 分子 | long | 分子です。 |
| 分母 | long | 分母。 |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


分数計算のイプシロン

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffRational approximateFraction(double value)
```


提供された値を分数に近似します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | 値です。 |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffRational approximateFraction(double value, double epsilon)
```


提供された値を分数に近似します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | 値です。 |
| イプシロン | double | 許容されるエラー。 |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffRational approximateFraction(float value)
```


提供された値を分数に近似します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | 値です。 |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffRational approximateFraction(float value, double epsilon)
```


提供された値を分数に近似します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | 値です。 |
| イプシロン | double | 許容されるエラー。 |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトがこのインスタンスと等しいかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するオブジェクトです。 |

**Returns:**
boolean -  指定された Object がこのインスタンスと等しい場合は true、そうでない場合は false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDenominator() {#getDenominator--}
```
public long getDenominator()
```


分母を取得します。

値: 分母。

**Returns:**
long
### getNominator() {#getNominator--}
```
public long getNominator()
```


分子を取得します。

値: 分子。

**Returns:**
long
### getValue() {#getValue--}
```
public float getValue()
```


浮動小数点値を取得します。

値: float 値。

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


double 値を取得します。

値: double 値。

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - このインスタンスのハッシュコード。ハッシュアルゴリズムやハッシュテーブルのようなデータ構造での使用に適しています。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


このインスタンスを表す  System.String  を返します。

**Returns:**
java.lang.String - このインスタンスを表す System.String。
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

