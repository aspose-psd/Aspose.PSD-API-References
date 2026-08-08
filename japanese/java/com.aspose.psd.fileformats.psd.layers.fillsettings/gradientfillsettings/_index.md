---
title: "GradientFillSettings"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "グラデーション塗りつぶし効果設定。"
type: docs
weight: 14
url: /ja/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

グラデーション塗りつぶし効果設定。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | 新しい [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) クラスのインスタンスを初期化します。 |
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
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | グラデーションの位置を正しく計算できるように、レイヤーコンテナの境界を取得または設定します。 |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | 現在の Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) 値に対応する **denormalized** グラデーションスケール（UI スケール）を計算して返します。 |
| [getDither()](#getDither--) | この [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) がディザリングかどうかを示す値を取得または設定します。 |
| [getFillType()](#getFillType--) | 塗りタイプ。 |
| [getGradient()](#getGradient--) | 特定のグラデーション定義インスタンス（ソリッド/ノイズ）を取得または設定します。 |
| [getGradientType()](#getGradientType--) | グラデーションのタイプを取得または設定します。 |
| [getHorizontalOffset()](#getHorizontalOffset--) | パーセンテージで水平オフセットを取得または設定します。 |
| [getInterpolationMethod()](#getInterpolationMethod--) | グラデーションの補間方法を取得または設定します。 |
| [getReverse()](#getReverse--) | この [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) が逆方向かどうかを示す値を取得または設定します。 |
| [getScale()](#getScale--) | **normalized** グラデーションスケール（パーセンテージ）を取得または設定します。 |
| [getVerticalOffset()](#getVerticalOffset--) | パーセンテージで垂直オフセットを取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | 値が変更されたことを通知します。 |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | [align with layer] が有効かどうかを示す値を取得または設定します。 |
| [setAngle(double value)](#setAngle-double-) | 角度を取得または設定します。 |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | グラデーションの位置を正しく計算できるように、レイヤーコンテナの境界を取得または設定します。 |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | 指定された非正規化スケール（UI）スケール値を **normalized** 等価に変換し、Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) に割り当てます。 |
| [setDither(boolean value)](#setDither-boolean-) | この [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) がディザリングかどうかを示す値を取得または設定します。 |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | 特定のグラデーション定義インスタンス（ソリッド/ノイズ）を取得または設定します。 |
| [setGradientType(int value)](#setGradientType-int-) | グラデーションのタイプを取得または設定します。 |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | パーセンテージで水平オフセットを取得または設定します。 |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | グラデーションの補間方法を取得または設定します。 |
| [setReverse(boolean value)](#setReverse-boolean-) | この [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) が逆方向かどうかを示す値を取得または設定します。 |
| [setScale(int value)](#setScale-int-) | **normalized** グラデーションスケール（パーセンテージ）を取得または設定します。 |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | パーセンテージで垂直オフセットを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


新しい [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) クラスのインスタンスを初期化します。

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
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


グラデーションの位置を正しく計算できるように、レイヤーコンテナの境界を取得または設定します。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


現在の Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) 値に対応する **denormalized** グラデーションスケール（UI スケール）を計算して返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | グラデーションの境界。 |

**Returns:**
int - Photoshop に表示されるパーセンテージの非正規化（UI）スケール。
### getDither() {#getDither--}
```
public final boolean getDither()
```


この [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) がディザリングかどうかを示す値を取得または設定します。

値: ディザリングの場合は true、そうでない場合は false。

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


塗りタイプ。

**Returns:**
int
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


特定のグラデーション定義インスタンス（ソリッド/ノイズ）を取得または設定します。

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
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
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


グラデーションの補間方法を取得または設定します。

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


この [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) が逆方向かどうかを示す値を取得または設定します。

値: 逆方向の場合は true、そうでない場合は false。

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


**normalized** グラデーションスケール（パーセンテージ）を取得または設定します。

**Returns:**
int
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

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


グラデーションの位置を正しく計算できるように、レイヤーコンテナの境界を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


指定された非正規化スケール（UI）スケール値を **normalized** 等価に変換し、Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) に割り当てます。変換は gradient\\u2019s の現在の Angle ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) と提供された fillArea を使用して正規化係数を計算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 非正規化スケール、Photoshop に表示されるパーセンテージの UI スケール； |
| fillArea | [Size](../../com.aspose.psd/size) | グラデーションの境界。 |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


この [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) がディザリングかどうかを示す値を取得または設定します。

値: ディザリングの場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


特定のグラデーション定義インスタンス（ソリッド/ノイズ）を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

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

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


グラデーションの補間方法を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


この [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) が逆方向かどうかを示す値を取得または設定します。

値: 逆方向の場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


**normalized** グラデーションスケール（パーセンテージ）を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

