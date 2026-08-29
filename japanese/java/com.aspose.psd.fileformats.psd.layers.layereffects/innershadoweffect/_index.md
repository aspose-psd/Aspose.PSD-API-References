---
title: "InnerShadowEffect"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "インナーシャドウレイヤーエフェクト"
type: docs
weight: 14
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.IShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class InnerShadowEffect implements IShadowEffect, IInternalLayerEffect
```

インナーシャドウレイヤーエフェクト
## メソッド

| メソッド | 説明 |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | 角度（度）を取得または設定します。 |
| [getBlendMode()](#getBlendMode--) | ブレンドモードを取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 色を取得または設定します。 |
| [getDistance()](#getDistance--) | 距離（ピクセル）を取得または設定します。 |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | 入力レイヤーのピクセル境界に基づいてエフェクトピクセルの境界を計算し、取得します。 |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | エンティティを取得します |
| [getEffectType()](#getEffectType--) | エフェクトのタイプを取得します |
| [getNoise()](#getNoise--) | ノイズを取得または設定します。 |
| [getOpacity()](#getOpacity--) | 不透明度を取得または設定します。 |
| [getSize()](#getSize--) | ぼかし値（ピクセル）を取得または設定します。 |
| [getSpread()](#getSpread--) | 広がり（チョーク）をパーセンテージで取得または設定します。 |
| [getUseGlobalLight()](#getUseGlobalLight--) | 値を取得または設定します。これは [use this angle in all of the layer effects] を使用するかどうかを示します。 |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | このインスタンスが表示されているかどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(int value)](#setAngle-int-) | 角度（度）を取得または設定します。 |
| [setBlendMode(long value)](#setBlendMode-long-) | ブレンドモードを取得または設定します。 |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 色を取得または設定します。 |
| [setDistance(int value)](#setDistance-int-) | 距離（ピクセル）を取得または設定します。 |
| [setNoise(int value)](#setNoise-int-) | ノイズを取得または設定します。 |
| [setOpacity(byte value)](#setOpacity-byte-) | 不透明度を取得または設定します。 |
| [setSize(int value)](#setSize-int-) | ぼかし値（ピクセル）を取得または設定します。 |
| [setSpread(int value)](#setSpread-int-) | 広がり（チョーク）をパーセンテージで取得または設定します。 |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | 値を取得または設定します。これは [use this angle in all of the layer effects] を使用するかどうかを示します。 |
| [setVisible(boolean value)](#setVisible-boolean-) | このインスタンスが表示されているかどうかを示す値を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static InnerShadowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| エンティティ | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect)
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
public final int getAngle()
```


角度（度）を取得または設定します。

値: 角度です。

**Returns:**
int
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
### getDistance() {#getDistance--}
```
public final int getDistance()
```


距離（ピクセル）を取得または設定します。

値: 距離。

**Returns:**
int
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
### getSize() {#getSize--}
```
public final int getSize()
```


ぼかし値（ピクセル）を取得または設定します。

値: サイズ。

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


広がり（チョーク）をパーセンテージで取得または設定します。

値: 広がり。

**Returns:**
int
### getUseGlobalLight() {#getUseGlobalLight--}
```
public final boolean getUseGlobalLight()
```


値を取得または設定します。これは [use this angle in all of the layer effects] を使用するかどうかを示します。

値:  true  [use global light] を使用する場合; それ以外の場合は false 。

**Returns:**
boolean
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




### setAngle(int value) {#setAngle-int-}
```
public final void setAngle(int value)
```


角度（度）を取得または設定します。

値: 角度です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

### setDistance(int value) {#setDistance-int-}
```
public final void setDistance(int value)
```


距離（ピクセル）を取得または設定します。

値: 距離。

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

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


ぼかし値（ピクセル）を取得または設定します。

値: サイズ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


広がり（チョーク）をパーセンテージで取得または設定します。

値: 広がり。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public final void setUseGlobalLight(boolean value)
```


値を取得または設定します。これは [use this angle in all of the layer effects] を使用するかどうかを示します。

値:  true  [use global light] を使用する場合; それ以外の場合は false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

