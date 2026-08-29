---
title: "IGradientFillSettings"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "グラデーション塗り設定の基本インターフェイス。"
type: docs
weight: 23
url: /ja/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

グラデーション塗り設定の基本インターフェイス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | [align with layer] が有効かどうかを示す値を取得または設定します。 |
| [getAngle()](#getAngle--) | 角度を取得または設定します。 |
| [getDither()](#getDither--) | この [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) がディザリングかどうかを示す値を取得または設定します。 |
| [getGradient()](#getGradient--) | 特定のグラデーション定義インスタンス（ソリッド/ノイズ）を取得または設定します。 |
| [getGradientType()](#getGradientType--) | グラデーションのタイプを取得または設定します。 |
| [getHorizontalOffset()](#getHorizontalOffset--) | 水平オフセットを取得または設定します。 |
| [getInterpolationMethod()](#getInterpolationMethod--) | グラデーションの補間方法を取得または設定します。 |
| [getReverse()](#getReverse--) | この [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) が逆かどうかを示す値を取得または設定します。 |
| [getScale()](#getScale--) | 正規化された **normalized** 勾配スケール（パーセント）を取得または設定します。 |
| [getVerticalOffset()](#getVerticalOffset--) | 垂直オフセットを取得または設定します。 |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | [align with layer] が有効かどうかを示す値を取得または設定します。 |
| [setAngle(double value)](#setAngle-double-) | 角度を取得または設定します。 |
| [setDither(boolean value)](#setDither-boolean-) | この [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) がディザリングかどうかを示す値を取得または設定します。 |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | 特定のグラデーション定義インスタンス（ソリッド/ノイズ）を取得または設定します。 |
| [setGradientType(int value)](#setGradientType-int-) | グラデーションのタイプを取得または設定します。 |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | 水平オフセットを取得または設定します。 |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | グラデーションの補間方法を取得または設定します。 |
| [setReverse(boolean value)](#setReverse-boolean-) | この [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) が逆かどうかを示す値を取得または設定します。 |
| [setScale(int value)](#setScale-int-) | 正規化された **normalized** 勾配スケール（パーセント）を取得または設定します。 |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | 垂直オフセットを取得または設定します。 |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


[align with layer] が有効かどうかを示す値を取得または設定します。

値:  true  if [align with layer]; otherwise,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


角度を取得または設定します。

値: 角度です。

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


この [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) がディザリングかどうかを示す値を取得または設定します。

値: ディザリングの場合は true、そうでない場合は false。

**Returns:**
boolean
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


特定のグラデーション定義インスタンス（ソリッド/ノイズ）を取得または設定します。

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


グラデーションのタイプを取得または設定します。

値: グラデーションのタイプです。

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


水平オフセットを取得または設定します。

値: 水平オフセット。

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


グラデーションの補間方法を取得または設定します。

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


この [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) が逆かどうかを示す値を取得または設定します。

値: 逆方向の場合は true、そうでない場合は false。

**Returns:**
boolean
### getScale() {#getScale--}
```
public abstract int getScale()
```


正規化された **normalized** 勾配スケール（パーセント）を取得または設定します。

値: スケール。

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


垂直オフセットを取得または設定します。

値: 垂直オフセット。

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


[align with layer] が有効かどうかを示す値を取得または設定します。

値:  true  if [align with layer]; otherwise,  false .

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


角度を取得または設定します。

値: 角度です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


この [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) がディザリングかどうかを示す値を取得または設定します。

値: ディザリングの場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


特定のグラデーション定義インスタンス（ソリッド/ノイズ）を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


グラデーションのタイプを取得または設定します。

値: グラデーションのタイプです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


水平オフセットを取得または設定します。

値: 水平オフセット。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


グラデーションの補間方法を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


この [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) が逆かどうかを示す値を取得または設定します。

値: 逆方向の場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


正規化された **normalized** 勾配スケール（パーセント）を取得または設定します。

値: スケール。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


垂直オフセットを取得または設定します。

値: 垂直オフセット。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

