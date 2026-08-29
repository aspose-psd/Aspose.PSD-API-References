---
title: "NoiseGradient"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ノイズグラデーション定義クラス。"
type: docs
weight: 19
url: /ja/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class NoiseGradient extends BaseGradient
```

ノイズグラデーション定義クラス。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [NoiseGradient()](#NoiseGradient--) | 新しいインスタンスを初期化します [NoiseGradient](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradient) クラス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | Color Model - RGB/HSB/LAB (3/4/6) を取得または設定します。 |
| [getExpansionCount()](#getExpansionCount--) | Expansion count ( = 2 for Photoshop 6.0) を取得または設定します。 |
| [getGradientMode()](#getGradientMode--) | このグラデーションのモードを取得します。 |
| [getGradientName()](#getGradientName--) | グラデーションの名前を取得または設定します。 |
| [getMaximumColor()](#getMaximumColor--) | PixelDataFormat の Maximum color を取得または設定します。 |
| [getMinimumColor()](#getMinimumColor--) | PixelDataFormat の Minimum color を取得または設定します。 |
| [getRndNumberSeed()](#getRndNumberSeed--) | ノイズ グラデーションの色を生成するために使用される乱数シードを取得または設定します |
| [getRoughness()](#getRoughness--) | 粗さ係数を取得または設定します。 |
| [getShowTransparency()](#getShowTransparency--) | 透明表示のフラグを取得または設定します。 |
| [getUseVectorColor()](#getUseVectorColor--) | ベクトルカラーの使用フラグを取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorModel(short value)](#setColorModel-short-) | Color Model - RGB/HSB/LAB (3/4/6) を取得または設定します。 |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Expansion count ( = 2 for Photoshop 6.0) を取得または設定します。 |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | グラデーションの名前を取得または設定します。 |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat の Maximum color を取得または設定します。 |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat の Minimum color を取得または設定します。 |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | ノイズ グラデーションの色を生成するために使用される乱数シードを取得または設定します |
| [setRoughness(int value)](#setRoughness-int-) | 粗さ係数を取得または設定します。 |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | 透明表示のフラグを取得または設定します。 |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | ベクトルカラーの使用フラグを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradient() {#NoiseGradient--}
```
public NoiseGradient()
```


新しいインスタンスを初期化します [NoiseGradient](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradient) クラス。

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Color Model - RGB/HSB/LAB (3/4/6) を取得または設定します。

**Returns:**
short
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Expansion count ( = 2 for Photoshop 6.0) を取得または設定します。

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
```


このグラデーションのモードを取得します。'Gradient Type' を 'Solid/Noise' (0/1) に決定します。

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


グラデーションの名前を取得または設定します。

値: グラデーションの名前です。

**Returns:**
java.lang.String
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


PixelDataFormat の Maximum color を取得または設定します。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


PixelDataFormat の Minimum color を取得または設定します。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


ノイズ グラデーションの色を生成するために使用される乱数シードを取得または設定します

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


粗さ係数を取得または設定します。

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


透明表示のフラグを取得または設定します。

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


ベクトルカラーの使用フラグを取得または設定します。

**Returns:**
boolean
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




### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Color Model - RGB/HSB/LAB (3/4/6) を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Expansion count ( = 2 for Photoshop 6.0) を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


グラデーションの名前を取得または設定します。

値: グラデーションの名前です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


PixelDataFormat の Maximum color を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


PixelDataFormat の Minimum color を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


ノイズ グラデーションの色を生成するために使用される乱数シードを取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


粗さ係数を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


透明表示のフラグを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


ベクトルカラーの使用フラグを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

