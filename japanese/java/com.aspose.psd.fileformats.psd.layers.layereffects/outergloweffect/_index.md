---
title: "OuterGlowEffect"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "外側の光彩レイヤーエフェクト"
type: docs
weight: 15
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

外側の光彩レイヤーエフェクト
## メソッド

| メソッド | 説明 |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | ブレンドモードを取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | 入力レイヤーのピクセル境界に基づいてエフェクトピクセルの境界を計算し、取得します。 |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | エンティティを取得します |
| [getEffectType()](#getEffectType--) | 効果タイプの型を取得します。 |
| [getFillColor()](#getFillColor--) | 色を取得または設定します。 |
| [getIntensity()](#getIntensity--) | 角度（度）を取得または設定します。 |
| [getJitter()](#getJitter--) | ノイズを取得または設定します。 |
| [getNoise()](#getNoise--) | ノイズを取得または設定します。 |
| [getOpacity()](#getOpacity--) | 不透明度を取得または設定します。 |
| [getRange()](#getRange--) | ノイズを取得または設定します。 |
| [getSize()](#getSize--) | ピクセル単位のぼかし値を取得します。 |
| [getSpread()](#getSpread--) | 強度をパーセンテージで取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | 有効な AntiAliasing 効果を取得または設定します。 |
| [isSoftBlend()](#isSoftBlend--) | [knocks out] かどうかを示す値を取得または設定します。 |
| [isVisible()](#isVisible--) | このインスタンスが表示されているかどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | 有効な AntiAliasing 効果を取得または設定します。 |
| [setBlendMode(long value)](#setBlendMode-long-) | ブレンドモードを取得または設定します。 |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | 色を取得または設定します。 |
| [setIntensity(int value)](#setIntensity-int-) | 角度（度）を取得または設定します。 |
| [setJitter(int value)](#setJitter-int-) | ノイズを取得または設定します。 |
| [setNoise(int value)](#setNoise-int-) | ノイズを取得または設定します。 |
| [setOpacity(byte value)](#setOpacity-byte-) | 不透明度を取得または設定します。 |
| [setRange(int value)](#setRange-int-) | ノイズを取得または設定します。 |
| [setSize(int value)](#setSize-int-) | ピクセル単位のぼかし値を取得します。 |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | [knocks out] かどうかを示す値を取得または設定します。 |
| [setSpread(int value)](#setSpread-int-) | 強度をパーセンテージで取得または設定します。 |
| [setVisible(boolean value)](#setVisible-boolean-) | このインスタンスが表示されているかどうかを示す値を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| エンティティ | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


ブレンドモードを取得または設定します。

値: ブレンドモード。

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


入力レイヤーのピクセル境界に基づいてエフェクトピクセルの境界を計算し、取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | レイヤーのピクセル境界。 |
| globalAngle | int | グローバル光角度を計算するためのグローバル角度です。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


エンティティを取得します

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


効果タイプの型を取得します。

**Returns:**
int
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


色を取得または設定します。

値: 色。

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


角度（度）を取得または設定します。

値: 角度です。

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


ノイズを取得または設定します。

**Returns:**
int
### getNoise() {#getNoise--}
```
public final int getNoise()
```


ノイズを取得または設定します。

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


不透明度を取得または設定します。

値: 不透明度です。

**Returns:**
byte
### getRange() {#getRange--}
```
public final int getRange()
```


ノイズを取得または設定します。

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


ピクセル単位のぼかし値を取得します。

値: サイズ。

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


強度をパーセンテージで取得または設定します。

値: 広がり。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAntiAliasing() {#isAntiAliasing--}
```
public final boolean isAntiAliasing()
```


有効な AntiAliasing 効果を取得または設定します。

値: 距離。

**Returns:**
boolean
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


[knocks out] かどうかを示す値を取得または設定します。

値: true は [knocks out] の場合、そうでなければ false です。

**Returns:**
boolean
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


このインスタンスが表示されているかどうかを示す値を取得または設定します。

Value:  true  このインスタンスが表示されている場合; それ以外の場合は  false .

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




### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public final void setAntiAliasing(boolean value)
```


有効な AntiAliasing 効果を取得または設定します。

値: 距離。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


ブレンドモードを取得または設定します。

値: ブレンドモード。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


色を取得または設定します。

値: 色。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


角度（度）を取得または設定します。

値: 角度です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


ノイズを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


ノイズを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


不透明度を取得または設定します。

値: 不透明度です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


ノイズを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


ピクセル単位のぼかし値を取得します。

値: サイズ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


[knocks out] かどうかを示す値を取得または設定します。

値: true は [knocks out] の場合、そうでなければ false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


強度をパーセンテージで取得または設定します。

値: 広がり。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


このインスタンスが表示されているかどうかを示す値を取得または設定します。

Value:  true  このインスタンスが表示されている場合; それ以外の場合は  false .

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

