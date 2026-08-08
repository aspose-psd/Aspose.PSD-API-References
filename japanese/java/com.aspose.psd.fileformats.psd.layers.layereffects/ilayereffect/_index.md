---
title: "ILayerEffect"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "レイヤー効果のインターフェイス"
type: docs
weight: 20
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

レイヤー効果のインターフェイス
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | ブレンドモードを取得または設定します。 |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | 入力レイヤーのピクセル境界に基づいてエフェクトピクセルの境界を計算し、取得します。 |
| [getEffectType()](#getEffectType--) | エフェクトのタイプを取得します |
| [getOpacity()](#getOpacity--) | 不透明度を取得または設定します（255 = 100%）。 |
| [isVisible()](#isVisible--) | このインスタンスが表示されているかどうかを示す値を取得または設定します。 |
| [setBlendMode(long value)](#setBlendMode-long-) | ブレンドモードを取得または設定します。 |
| [setOpacity(byte value)](#setOpacity-byte-) | 不透明度を取得または設定します（255 = 100%）。 |
| [setVisible(boolean value)](#setVisible-boolean-) | このインスタンスが表示されているかどうかを示す値を取得または設定します。 |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


ブレンドモードを取得または設定します。

値: ブレンドモード。

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


入力レイヤーのピクセル境界に基づいてエフェクトピクセルの境界を計算し、取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | レイヤーのピクセル境界。 |
| globalAngle | int | グローバル光角度を計算するためのグローバル角度です。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


エフェクトのタイプを取得します

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


不透明度を取得または設定します（255 = 100%）。

値: 不透明度です。

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


このインスタンスが表示されているかどうかを示す値を取得または設定します。

Value:  true  このインスタンスが表示されている場合; それ以外の場合は  false .

**Returns:**
boolean
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


ブレンドモードを取得または設定します。

値: ブレンドモード。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


不透明度を取得または設定します（255 = 100%）。

値: 不透明度です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


このインスタンスが表示されているかどうかを示す値を取得または設定します。

Value:  true  このインスタンスが表示されている場合; それ以外の場合は  false .

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

