---
title: "StrokeEffect"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "PSD レイヤー用の Adobe Photoshop ストローク効果です。"
type: docs
weight: 17
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

PSDレイヤー用のAdobe® Photoshop®ストロークエフェクトです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | ブレンドモードを取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | 入力レイヤーのピクセル境界に基づいてエフェクトピクセルの境界を計算し、取得します。 |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | エンティティを取得します |
| [getEffectType()](#getEffectType--) | エフェクトのタイプを取得します |
| [getFillSettings()](#getFillSettings--) | 塗りつぶし設定を取得または設定します。 |
| [getOpacity()](#getOpacity--) | 不透明度を取得または設定します。 |
| [getOverprint()](#getOverprint--) | この [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) が現在のレイヤー内容に対してストロークをブレンドするかどうかを示す値を取得または設定します。 |
| [getPosition()](#getPosition--) | ストローク効果の位置を取得または設定し、ストロークを PSD レイヤーコンテンツに合わせて整列させます。 |
| [getSize()](#getSize--) | ストローク効果の幅を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | このインスタンスが表示されているかどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | ブレンドモードを取得または設定します。 |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | 塗りつぶし設定を取得または設定します。 |
| [setOpacity(byte value)](#setOpacity-byte-) | 不透明度を取得または設定します。 |
| [setOverprint(boolean value)](#setOverprint-boolean-) | この [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) が現在のレイヤー内容に対してストロークをブレンドするかどうかを示す値を取得または設定します。 |
| [setPosition(short value)](#setPosition-short-) | ストローク効果の位置を取得または設定し、ストロークを PSD レイヤーコンテンツに合わせて整列させます。 |
| [setSize(int value)](#setSize-int-) | ストローク効果の幅を取得または設定します。 |
| [setVisible(boolean value)](#setVisible-boolean-) | このインスタンスが表示されているかどうかを示す値を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| エンティティ | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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


エフェクトのタイプを取得します

**Returns:**
int
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


塗りつぶし設定を取得または設定します。

値: 塗り設定。

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


不透明度を取得または設定します。

値: 不透明度です。

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


この [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) が現在のレイヤー内容に対してストロークをブレンドするかどうかを示す値を取得または設定します。

値:  true  ストロークを現在のレイヤー内容にブレンドする必要がある場合; それ以外の場合は  false 。

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public final short getPosition()
```


ストローク効果の位置を取得または設定し、ストロークを PSD レイヤーコンテンツに合わせて整列させます。値は、PSD レイヤーコンテンツの内部にストロークを描画するための [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside)、外部に描画するための [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside)、内部と外部の両方に描画するための [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) のいずれかにできます。

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


ストローク効果の幅を取得または設定します。

値: ストローク効果の幅。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


塗りつぶし設定を取得または設定します。

値: 塗り設定。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

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

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


この [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) が現在のレイヤー内容に対してストロークをブレンドするかどうかを示す値を取得または設定します。

値:  true  ストロークを現在のレイヤー内容にブレンドする必要がある場合; それ以外の場合は  false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


ストローク効果の位置を取得または設定し、ストロークを PSD レイヤーコンテンツに合わせて整列させます。値は、PSD レイヤーコンテンツの内部にストロークを描画するための [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside)、外部に描画するための [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside)、内部と外部の両方に描画するための [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) のいずれかにできます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


ストローク効果の幅を取得または設定します。

値: ストローク効果の幅。

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

