---
title: "GradientHelper"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "グラデーションプロパティ用データの変換を実装するヘルパークラスです。"
type: docs
weight: 34
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

グラデーションプロパティ用データの変換を実装するヘルパークラスです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | HSBL カラーモデルのノイズグラデーション用整数定数。 |
| [IntModelLAB](#IntModelLAB) | LBCL カラーモデルのノイズグラデーション用整数定数。 |
| [IntModelRGB](#IntModelRGB) | RGBC カラーモデルのノイズグラデーション用整数定数。 |
| [StrGradientNoise](#StrGradientNoise) | ノイズグラデーション文字列定数。 |
| [StrGradientSolid](#StrGradientSolid) | ソリッドグラデーション文字列定数。 |
| [StrModelHSB](#StrModelHSB) | ノイズグラデーション用 HSBL カラーモデル文字列定数。 |
| [StrModelLAB](#StrModelLAB) | ノイズグラデーション用 LBCL カラーモデル文字列定数。 |
| [StrModelRGB](#StrModelRGB) | ノイズグラデーション用 RGBC カラーモデル文字列定数。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | GradientKind の値を文字列に変換します。 |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | ノイズカラーモデルの整数値を NoiseColorModel に変換します。 |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | NoiseColorModel インスタンスをノイズカラーモデルの整数値に変換します。 |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | NoiseColorModel の値を文字列に変換します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | 文字列の値を GradientKind に変換します。 |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | 文字列の値を NoiseColorModel に変換します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientHelper() {#GradientHelper--}
```
public GradientHelper()
```


### IntModelHSB {#IntModelHSB}
```
public static final short IntModelHSB
```


HSBL カラーモデルのノイズグラデーション用整数定数。

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


LBCL カラーモデルのノイズグラデーション用整数定数。

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


RGBC カラーモデルのノイズグラデーション用整数定数。

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


ノイズグラデーション文字列定数。

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


ソリッドグラデーション文字列定数。

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


ノイズグラデーション用 HSBL カラーモデル文字列定数。

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


ノイズグラデーション用 LBCL カラーモデル文字列定数。

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


ノイズグラデーション用 RGBC カラーモデル文字列定数。

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
### gradientKindToStr(int gradientKind) {#gradientKindToStr-int-}
```
public static String gradientKindToStr(int gradientKind)
```


GradientKind の値を文字列に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| gradientKind | int | GradientKind の値。 |

**Returns:**
java.lang.String - 文字列の値。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intToNoiseColorModel(short colorModel) {#intToNoiseColorModel-short-}
```
public static short intToNoiseColorModel(short colorModel)
```


ノイズカラーモデルの整数値を NoiseColorModel に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorModel | short | ノイズカラーモデルの整数値。 |

**Returns:**
short - NoiseColorModel インスタンス。
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


NoiseColorModel インスタンスをノイズカラーモデルの整数値に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorModel | short | NoiseColorModel インスタンス。 |

**Returns:**
short - ノイズグラデーションカラーモデルの整数値。
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


NoiseColorModel の値を文字列に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorModel | short | NoiseColorModel の値。 |

**Returns:**
java.lang.String - カラーモデルの文字列値。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### strToGradientKind(String str) {#strToGradientKind-java.lang.String-}
```
public static int strToGradientKind(String str)
```


文字列の値を GradientKind に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| str | java.lang.String | 文字列値。 |

**Returns:**
int - GradientKind の値。
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


文字列の値を NoiseColorModel に変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorModel | java.lang.String | 文字列値。 |

**Returns:**
short - NoiseColorModel の値。
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

