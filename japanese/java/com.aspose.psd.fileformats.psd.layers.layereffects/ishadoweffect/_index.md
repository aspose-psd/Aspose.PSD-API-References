---
title: "IShadowEffect"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "シャドウレイヤー効果のインターフェイス"
type: docs
weight: 21
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect)
```
public interface IShadowEffect extends ILayerEffect
```

シャドウレイヤー効果のインターフェイス
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAngle()](#getAngle--) | 角度（度）を取得または設定します。 |
| [getColor()](#getColor--) | 色を取得または設定します。 |
| [getDistance()](#getDistance--) | 距離（ピクセル）を取得または設定します。 |
| [getNoise()](#getNoise--) | ノイズを取得または設定します。 |
| [getSize()](#getSize--) | ぼかし値（ピクセル）を取得または設定します。 |
| [getSpread()](#getSpread--) | 強度をパーセンテージで取得または設定します。 |
| [getUseGlobalLight()](#getUseGlobalLight--) | 値を取得または設定します。これは [use this angle in all of the layer effects] を使用するかどうかを示します。 |
| [setAngle(int value)](#setAngle-int-) | 角度（度）を取得または設定します。 |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 色を取得または設定します。 |
| [setDistance(int value)](#setDistance-int-) | 距離（ピクセル）を取得または設定します。 |
| [setNoise(int value)](#setNoise-int-) | ノイズを取得または設定します。 |
| [setSize(int value)](#setSize-int-) | ぼかし値（ピクセル）を取得または設定します。 |
| [setSpread(int value)](#setSpread-int-) | 強度をパーセンテージで取得または設定します。 |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | 値を取得または設定します。これは [use this angle in all of the layer effects] を使用するかどうかを示します。 |
### getAngle() {#getAngle--}
```
public abstract int getAngle()
```


角度（度）を取得または設定します。

値: 角度です。

**Returns:**
int
### getColor() {#getColor--}
```
public abstract Color getColor()
```


色を取得または設定します。

値: 色。

**Returns:**
[Color](../../com.aspose.psd/color)
### getDistance() {#getDistance--}
```
public abstract int getDistance()
```


距離（ピクセル）を取得または設定します。

値: 距離。

**Returns:**
int
### getNoise() {#getNoise--}
```
public abstract int getNoise()
```


ノイズを取得または設定します。

**Returns:**
int
### getSize() {#getSize--}
```
public abstract int getSize()
```


ぼかし値（ピクセル）を取得または設定します。

値: サイズ。

**Returns:**
int
### getSpread() {#getSpread--}
```
public abstract int getSpread()
```


強度をパーセンテージで取得または設定します。

値: 広がり。

**Returns:**
int
### getUseGlobalLight() {#getUseGlobalLight--}
```
public abstract boolean getUseGlobalLight()
```


値を取得または設定します。これは [use this angle in all of the layer effects] を使用するかどうかを示します。

値:  true  [use global light] を使用する場合; それ以外の場合は false 。

**Returns:**
boolean
### setAngle(int value) {#setAngle-int-}
```
public abstract void setAngle(int value)
```


角度（度）を取得または設定します。

値: 角度です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public abstract void setColor(Color value)
```


色を取得または設定します。

値: 色。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDistance(int value) {#setDistance-int-}
```
public abstract void setDistance(int value)
```


距離（ピクセル）を取得または設定します。

値: 距離。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setNoise(int value) {#setNoise-int-}
```
public abstract void setNoise(int value)
```


ノイズを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSize(int value) {#setSize-int-}
```
public abstract void setSize(int value)
```


ぼかし値（ピクセル）を取得または設定します。

値: サイズ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setSpread(int value) {#setSpread-int-}
```
public abstract void setSpread(int value)
```


強度をパーセンテージで取得または設定します。

値: 広がり。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public abstract void setUseGlobalLight(boolean value)
```


値を取得または設定します。これは [use this angle in all of the layer effects] を使用するかどうかを示します。

値:  true  [use global light] を使用する場合; それ以外の場合は false 。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

