---
title: "NoiseGradientFillSettings"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ノイズグラデーション定義クラス。"
type: docs
weight: 18
url: /ja/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

ノイズグラデーション定義クラス。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | 新しいインスタンスとして [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) クラスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | [align with layer] が有効かどうかを示す値を取得または設定します。 |
| [getAngle()](#getAngle--) | 角度を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | Color Model - RGB/HSB/LAB (3/4/6) を取得または設定します。 |
| [getDither()](#getDither--) | この [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) がディザリングされているかどうかを示す値を取得または設定します。 |
| [getExpansionCount()](#getExpansionCount--) | Expansion count ( = 2 for Photoshop 6.0) を取得または設定します。 |
| [getFillType()](#getFillType--) | 塗りタイプ。 |
| [getGradientMode()](#getGradientMode--) | このグラデーションのモードを取得します。 |
| [getGradientName()](#getGradientName--) | グラデーションの名前を取得または設定します。 |
| [getGradientType()](#getGradientType--) | グラデーションのタイプを取得または設定します。 |
| [getHorizontalOffset()](#getHorizontalOffset--) | パーセンテージで水平オフセットを取得または設定します。 |
| [getMaximumColor()](#getMaximumColor--) | PixelDataFormat の Maximum color を取得または設定します。 |
| [getMinimumColor()](#getMinimumColor--) | PixelDataFormat の Minimum color を取得または設定します。 |
| [getReverse()](#getReverse--) | この [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) が逆かどうかを示す値を取得または設定します。 |
| [getRndNumberSeed()](#getRndNumberSeed--) | ノイズ グラデーションの色を生成するために使用される乱数シードを取得または設定します |
| [getRoughness()](#getRoughness--) | 粗さ係数を取得または設定します。 |
| [getScale()](#getScale--) | スケールを取得または設定します。 |
| [getShowTransparency()](#getShowTransparency--) | 透明表示のフラグを取得または設定します。 |
| [getUseVectorColor()](#getUseVectorColor--) | ベクトルカラーの使用フラグを取得または設定します。 |
| [getVerticalOffset()](#getVerticalOffset--) | パーセンテージで垂直オフセットを取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | 値が変更されたことを通知します。 |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | [align with layer] が有効かどうかを示す値を取得または設定します。 |
| [setAngle(double value)](#setAngle-double-) | 角度を取得または設定します。 |
| [setColorModel(short value)](#setColorModel-short-) | Color Model - RGB/HSB/LAB (3/4/6) を取得または設定します。 |
| [setDither(boolean value)](#setDither-boolean-) | この [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) がディザリングされているかどうかを示す値を取得または設定します。 |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Expansion count ( = 2 for Photoshop 6.0) を取得または設定します。 |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | このグラデーションのモードを取得します。 |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | グラデーションの名前を取得または設定します。 |
| [setGradientType(int value)](#setGradientType-int-) | グラデーションのタイプを取得または設定します。 |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | パーセンテージで水平オフセットを取得または設定します。 |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat の Maximum color を取得または設定します。 |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat の Minimum color を取得または設定します。 |
| [setReverse(boolean value)](#setReverse-boolean-) | この [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) が逆かどうかを示す値を取得または設定します。 |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | ノイズ グラデーションの色を生成するために使用される乱数シードを取得または設定します |
| [setRoughness(int value)](#setRoughness-int-) | 粗さ係数を取得または設定します。 |
| [setScale(int value)](#setScale-int-) | スケールを取得または設定します。 |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | 透明表示のフラグを取得または設定します。 |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | ベクトルカラーの使用フラグを取得または設定します。 |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | パーセンテージで垂直オフセットを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


新しいインスタンスとして [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) クラスを初期化します。

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


[align with layer] が有効かどうかを示す値を取得または設定します。

値:  true  if [align with layer]; otherwise,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


角度を取得または設定します。

**Returns:**
double
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
### getDither() {#getDither--}
```
public final boolean getDither()
```


この [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) がディザリングされているかどうかを示す値を取得または設定します。

値: ディザリングの場合は true、そうでない場合は false。

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Expansion count ( = 2 for Photoshop 6.0) を取得または設定します。

**Returns:**
short
### getFillType() {#getFillType--}
```
public int getFillType()
```


塗りタイプ。

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
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
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


グラデーションのタイプを取得または設定します。

値: グラデーションのタイプです。

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


パーセンテージで水平オフセットを取得または設定します。

値: 水平オフセット。

**Returns:**
double
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
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


この [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) が逆かどうかを示す値を取得または設定します。

値: 逆方向の場合は true、そうでない場合は false。

**Returns:**
boolean
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
### getScale() {#getScale--}
```
public final int getScale()
```


スケールを取得または設定します。

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
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


パーセンテージで垂直オフセットを取得または設定します。

値: 垂直オフセット。

**Returns:**
double
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


値が変更されたことを通知します。

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


[align with layer] が有効かどうかを示す値を取得または設定します。

値:  true  if [align with layer]; otherwise,  false .

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


角度を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Color Model - RGB/HSB/LAB (3/4/6) を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


この [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) がディザリングされているかどうかを示す値を取得または設定します。

値: ディザリングの場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Expansion count ( = 2 for Photoshop 6.0) を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


このグラデーションのモードを取得します。'Gradient Type' を 'Solid/Noise' (0/1) に決定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


グラデーションのタイプを取得または設定します。

値: グラデーションのタイプです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


パーセンテージで水平オフセットを取得または設定します。

値: 水平オフセット。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

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

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


この [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) が逆かどうかを示す値を取得または設定します。

値: 逆方向の場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


スケールを取得または設定します。

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

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


パーセンテージで垂直オフセットを取得または設定します。

値: 垂直オフセット。

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

