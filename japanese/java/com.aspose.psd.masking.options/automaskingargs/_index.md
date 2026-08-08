---
title: "AutoMaskingArgs"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "自動マスキングメソッドに指定される引数を表します。"
type: docs
weight: 11
url: /ja/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

自動マスキングメソッドに指定される引数を表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | イテレーションの最大数を取得します。 |
| [getNumberOfObjects()](#getNumberOfObjects--) | 初期画像を分離するオブジェクト数を取得します（オプション）。デフォルト値は 2（オブジェクトと背景）です。 |
| [getObjectsPoints()](#getObjectsPoints--) | 分離されたオブジェクトに属するポイントを取得します（オプション）。初期画像のNumberOfObjectsオブジェクトに属するNumberOfObjects座標。 |
| [getObjectsRectangles()](#getObjectsRectangles--) | 分離されたオブジェクトに属するオブジェクトの矩形を取得します（オプション）。 |
| [getOrphanedPoints()](#getOrphanedPoints--) | もはやどのオブジェクトにも属さないポイントを取得します（オプション）。 |
| [getPrecision()](#getPrecision--) | セグメンテーション手法の精度を取得します（オプション）。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | 最大反復回数を設定します。 |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | 初期画像を分離するオブジェクト数を設定します（オプション）。デフォルト値は2（オブジェクトと背景）です。 |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | 分離されたオブジェクトに属するポイントを設定します（オプション）。初期画像のNumberOfObjectsオブジェクトに属するNumberOfObjects座標。 |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | 分離されたオブジェクトに属するオブジェクトの矩形を設定します（オプション）。 |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | もはやどのオブジェクトにも属さないポイントを設定します（オプション）。 |
| [setPrecision(double value)](#setPrecision-double-) | セグメンテーション手法の精度を設定します（オプション）。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


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
### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


イテレーションの最大数を取得します。

値: 最大反復回数。

**Returns:**
int - 最大反復回数。
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


初期画像を分離するオブジェクト数を取得します（オプション）。デフォルト値は 2（オブジェクトと背景）です。

値: オブジェクト数。

**Returns:**
int - 初期画像を分離するオブジェクト数（オプション）、デフォルト値は2（オブジェクトと背景）。
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


分離されたオブジェクトに属するポイントを取得します（オプション）。初期画像のNumberOfObjectsオブジェクトに属するNumberOfObjects座標。このパラメータはセグメンテーション手法の精度を向上させるために使用されます。

値: オブジェクトのポイント。

**Returns:**
com.aspose.psd.Point[][] - 分離されたオブジェクトに属するポイント（オプション）。初期画像のNumberOfObjectsオブジェクトに属するNumberOfObjects座標。
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


分離されたオブジェクトに属するオブジェクトの矩形を取得します（オプション）。このパラメータはセグメンテーション手法の精度を向上させるために使用されます。

値: オブジェクトの矩形。

**Returns:**
com.aspose.psd.Rectangle[] - 分離されたオブジェクトに属するオブジェクトの矩形（オプション）。
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


もはやどのオブジェクトにも属さないポイントを取得します（オプション）。このパラメータは再セグメンテーションの場合にのみ使用されます。

値: 孤立したポイント。

**Returns:**
com.aspose.psd.Point[] - もはやどのオブジェクトにも属さないポイント（オプション）。
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


セグメンテーション手法の精度を取得します（オプション）。

値: セグメンテーション手法の精度（オプション）。

**Returns:**
double - セグメンテーション手法の精度（オプション）。
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




### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


最大反復回数を設定します。

値: 最大反復回数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 最大反復回数。 |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


初期画像を分離するオブジェクト数を設定します（オプション）。デフォルト値は2（オブジェクトと背景）です。

値: オブジェクト数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 初期画像を分割するオブジェクト数（オプション）、デフォルト値は2（オブジェクトと背景）です。 |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


分離されたオブジェクトに属する点を設定します（オプション）。NumberOfObjects の座標は初期画像の NumberOfObjects オブジェクトに属します。このパラメーターはセグメンテーション手法の精度を向上させるために使用されます。

値: オブジェクトのポイント。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | 分離されたオブジェクトに属する点（オプション）NumberOfObjects の座標は初期画像の NumberOfObjects オブジェクトに属します。 |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


分離されたオブジェクトに属するオブジェクトの矩形を設定します（オプション）。このパラメーターはセグメンテーション手法の精度を向上させるために使用されます。

値: オブジェクトの矩形。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | 分離されたオブジェクトに属するオブジェクトの矩形（オプション）。 |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


もはやどのオブジェクトにも属さない点を設定します（オプション）。このパラメーターは再セグメンテーションの場合にのみ使用されます。

値: 孤立したポイント。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | もはやどのオブジェクトにも属さない点（オプション）。 |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


セグメンテーション手法の精度を設定します（オプション）。

値: セグメンテーション手法の精度（オプション）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | セグメンテーション手法の精度（オプション）。 |

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

