---
title: "ColorOverlayEffect"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "カラーオーバーレイレイヤーエフェクト"
type: docs
weight: 11
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class ColorOverlayEffect implements ILayerEffect, IInternalLayerEffect
```

カラーオーバーレイレイヤーエフェクト
## メソッド

| メソッド | 説明 |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | ブレンドモードを取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 色を取得または設定します。 |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | 入力レイヤーのピクセル境界に基づいてエフェクトピクセルの境界を計算し、取得します。 |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | エンティティを取得します |
| [getEffectType()](#getEffectType--) | エフェクトのタイプを取得します |
| [getOpacity()](#getOpacity--) | 不透明度を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | このインスタンスが表示されているかどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | ブレンドモードを取得または設定します。 |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 色を取得または設定します。 |
| [setOpacity(byte value)](#setOpacity-byte-) | 不透明度を取得または設定します。 |
| [setVisible(boolean value)](#setVisible-boolean-) | このインスタンスが表示されているかどうかを示す値を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static ColorOverlayEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| エンティティ | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect)
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
### getColor() {#getColor--}
```
public final Color getColor()
```


色を取得または設定します。

値: 色。

**Returns:**
[Color](../../com.aspose.psd/color)
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
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


不透明度を取得または設定します。

値: 不透明度です。

**Returns:**
byte
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

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


色を取得または設定します。

値: 色。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

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

