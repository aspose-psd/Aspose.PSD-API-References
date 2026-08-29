---
title: "RdOptimizerSettings"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "RD オプティマイザー設定クラスです"
type: docs
weight: 22
url: /ja/java/com.aspose.psd.imageoptions/rdoptimizersettings/
---

**Inheritance:**
java.lang.Object
```
public class RdOptimizerSettings
```

RD オプティマイザー設定クラスです
## Constructors

| Constructor | 説明 |
| --- | --- |
| [RdOptimizerSettings()](#RdOptimizerSettings--) | RdOptimizerSettings クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [create()](#create--) | このインスタンスを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBppMax()](#getBppMax--) | ビット/ピクセルで考慮する最大 R 値を取得します |
| [getBppScale()](#getBppScale--) | BPP（ビット/ピクセル）のスケール係数を取得します。 |
| [getClass()](#getClass--) |  |
| [getDcClamp_internalized()](#getDcClamp-internalized--) | ブロック内の左上ピクセルの量子化値範囲を制限するための DC クランプ値を取得します。 |
| [getDiscretizedBppMax()](#getDiscretizedBppMax--) | 考慮する最大 R 値を取得します。 |
| [getMaxChannel_internalized()](#getMaxChannel-internalized--) | 使用する最大カラーチャンネル数を取得します。 |
| [getMaxPixelValue()](#getMaxPixelValue--) | 最大ピクセル値を取得します。 |
| [getMaxQ()](#getMaxQ--) | 最大量子化値を取得します。 |
| [getMinQ()](#getMinQ--) | 許容される最小量子化値を取得します。 |
| [getPsnrMax()](#getPsnrMax--) | PSNR の最大期待値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBppMax(double value)](#setBppMax-double-) | ビット/ピクセルで考慮する最大 R 値を設定します |
| [setBppScale(int value)](#setBppScale-int-) | BPP（ビット/ピクセル）のスケール係数を設定します。 |
| [setMaxChannel_internalized(int value)](#setMaxChannel-internalized-int-) | 使用する最大カラーチャンネル数を設定します。 |
| [setMaxQ(int value)](#setMaxQ-int-) | 最大量子化値を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RdOptimizerSettings() {#RdOptimizerSettings--}
```
public RdOptimizerSettings()
```


RdOptimizerSettings クラスの新しいインスタンスを初期化します。

### create() {#create--}
```
public static RdOptimizerSettings create()
```


このインスタンスを作成します。

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - returns RDOptimizerSettings class instance
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
### getBppMax() {#getBppMax--}
```
public double getBppMax()
```


ビット/ピクセルで考慮する最大 R 値を取得します

**Returns:**
double - ビット/ピクセルで考慮する最大 R 値です。
### getBppScale() {#getBppScale--}
```
public int getBppScale()
```


BPP（ビット/ピクセル）のスケール係数を取得します。

**Returns:**
int - BPP スケールです。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDcClamp_internalized() {#getDcClamp-internalized--}
```
public int getDcClamp_internalized()
```


ブロック内の左上ピクセルの量子化値範囲を制限するための DC クランプ値を取得します。

**Returns:**
int - DC クランプ値です。
### getDiscretizedBppMax() {#getDiscretizedBppMax--}
```
public int getDiscretizedBppMax()
```


考慮する最大 R 値を取得します。

**Returns:**
int - 考慮対象となる最大のR値。
### getMaxChannel_internalized() {#getMaxChannel-internalized--}
```
public int getMaxChannel_internalized()
```


使用する最大カラーチャンネル数を取得します。

**Returns:**
int - 最大のカラーチャネルインデックス。
### getMaxPixelValue() {#getMaxPixelValue--}
```
public int getMaxPixelValue()
```


最大ピクセル値を取得します。

**Returns:**
int - 最大のピクセル値。
### getMaxQ() {#getMaxQ--}
```
public int getMaxQ()
```


最大量子化値を取得します。

**Returns:**
int - 最大の量子化値。
### getMinQ() {#getMinQ--}
```
public int getMinQ()
```


許容される最小量子化値を取得します。

**Returns:**
int - 許容される最小の量子化値。
### getPsnrMax() {#getPsnrMax--}
```
public int getPsnrMax()
```


PSNR の最大期待値を取得します。

**Returns:**
int - 最大のピクセル値。
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




### setBppMax(double value) {#setBppMax-double-}
```
public void setBppMax(double value)
```


ビット/ピクセルで考慮する最大 R 値を設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | ビット/ピクセル単位で考慮される最大のR値。 |

### setBppScale(int value) {#setBppScale-int-}
```
public void setBppScale(int value)
```


BPP（ビット/ピクセル）のスケール係数を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | BPPスケール。 |

### setMaxChannel_internalized(int value) {#setMaxChannel-internalized-int-}
```
public void setMaxChannel_internalized(int value)
```


使用する最大カラーチャンネル数を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 最大のカラーチャネルインデックス。 |

### setMaxQ(int value) {#setMaxQ-int-}
```
public void setMaxQ(int value)
```


最大量子化値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 最大の量子化値。 |

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

