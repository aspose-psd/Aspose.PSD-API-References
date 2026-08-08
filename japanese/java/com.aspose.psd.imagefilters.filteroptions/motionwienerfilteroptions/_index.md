---
title: "MotionWienerFilterOptions"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "デコンボリューションフィルターオプション     動きのぼかし除去"
type: docs
weight: 18
url: /ja/java/com.aspose.psd.imagefilters.filteroptions/motionwienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class MotionWienerFilterOptions extends DeconvolutionFilterOptions
```

Deconvolution filter options デブラー モーション
## Constructors

| Constructor | 説明 |
| --- | --- |
| [MotionWienerFilterOptions(int length, double smooth, double angle)](#MotionWienerFilterOptions-int-double-double-) | MotionWienerFilterOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | 角度（gradus）を取得または設定します。 |
| [getBrightness()](#getBrightness--) | brightness を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | この [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) がグレースケールかどうかを示す値を取得または設定します。 |
| [getLength()](#getLength--) | 長さを取得または設定します。 |
| [getSmooth()](#getSmooth--) | smooth を取得または設定します。 |
| [getSnr()](#getSnr--) | SNR（信号対雑音比）を取得または設定します。推奨範囲 0.002 - 0.009、デフォルト値 = 0.007 |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | このインスタンスが部分的にロードされているかどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(double value)](#setAngle-double-) | 角度（gradus）を取得または設定します。 |
| [setBrightness(double value)](#setBrightness-double-) | brightness を取得または設定します。 |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | この [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) がグレースケールかどうかを示す値を取得または設定します。 |
| [setLength(int value)](#setLength-int-) | 長さを取得または設定します。 |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | このインスタンスが部分的にロードされているかどうかを示す値を取得します。 |
| [setSmooth(double value)](#setSmooth-double-) | smooth を取得または設定します。 |
| [setSnr(double value)](#setSnr-double-) | SNR（信号対雑音比）を取得または設定します。推奨範囲 0.002 - 0.009、デフォルト値 = 0.007 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MotionWienerFilterOptions(int length, double smooth, double angle) {#MotionWienerFilterOptions-int-double-double-}
```
public MotionWienerFilterOptions(int length, double smooth, double angle)
```


MotionWienerFilterOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| length | int | 長さ。 |
| smooth | double | smoothです。 |
| 角度 | double | 角度（gradus）です。 |

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
### getAngle() {#getAngle--}
```
public double getAngle()
```


角度（gradus）を取得または設定します。

値: 角度です。

**Returns:**
double
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


明るさを取得または設定します。推奨範囲 1 - 1.5、デフォルト値 = 1.15

値: brightness。

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


この [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) がグレースケールかどうかを示す値を取得または設定します。グレースケールモードまたはRGBモードを返します。

値:  true  がグレースケールの場合、そうでなければ  false です。

**Returns:**
boolean
### getLength() {#getLength--}
```
public int getLength()
```


長さを取得または設定します。

値: 長さ。

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


smooth を取得または設定します。

値: smoothです。

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


SNR（信号対雑音比）を取得または設定します。推奨範囲 0.002 - 0.009、デフォルト値 = 0.007

値: SNRです。

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPartialLoaded() {#isPartialLoaded--}
```
public final boolean isPartialLoaded()
```


このインスタンスが部分的にロードされているかどうかを示す値を取得します。

値:  true  がこのインスタンスが部分的にロードされている場合、そうでなければ  false です。

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




### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```


角度（gradus）を取得または設定します。

値: 角度です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


明るさを取得または設定します。推奨範囲 1 - 1.5、デフォルト値 = 1.15

値: brightness。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


この [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) がグレースケールかどうかを示す値を取得または設定します。グレースケールモードまたはRGBモードを返します。

値:  true  がグレースケールの場合、そうでなければ  false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


長さを取得または設定します。

値: 長さ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


このインスタンスが部分的にロードされているかどうかを示す値を取得します。

値:  true  がこのインスタンスが部分的にロードされている場合、そうでなければ  false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


smooth を取得または設定します。

値: smoothです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


SNR（信号対雑音比）を取得または設定します。推奨範囲 0.002 - 0.009、デフォルト値 = 0.007

値: SNRです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

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

