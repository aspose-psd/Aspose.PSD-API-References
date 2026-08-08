---
title: "IGradientTransparencyPoint"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "塗り設定の基本インターフェイス"
type: docs
weight: 24
url: /ja/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/
---
```
public interface IGradientTransparencyPoint
```

塗り設定の基本インターフェイス
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLocation()](#getLocation--) | 位置を取得または設定します。 |
| [getMedianPointLocation()](#getMedianPointLocation--) | 中央値の位置を取得または設定します。 |
| [getOpacity()](#getOpacity--) | 不透明度を取得または設定します。 |
| [setLocation(int value)](#setLocation-int-) | 位置を取得または設定します。 |
| [setMedianPointLocation(int value)](#setMedianPointLocation-int-) | 中央値の位置を取得または設定します。 |
| [setOpacity(double value)](#setOpacity-double-) | 不透明度を取得または設定します。 |
### getLocation() {#getLocation--}
```
public abstract int getLocation()
```


位置を取得または設定します。値の範囲は 0〜4096 です。

値: 位置です。

**Returns:**
int
### getMedianPointLocation() {#getMedianPointLocation--}
```
public abstract int getMedianPointLocation()
```


中央値の位置を取得または設定します。値の範囲は 0〜4096 です。

値: 中央値の位置です。

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract double getOpacity()
```


不透明度を取得または設定します。

値: 不透明度です。

**Returns:**
double
### setLocation(int value) {#setLocation-int-}
```
public abstract void setLocation(int value)
```


位置を取得または設定します。値の範囲は 0〜4096 です。

値: 位置です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMedianPointLocation(int value) {#setMedianPointLocation-int-}
```
public abstract void setMedianPointLocation(int value)
```


中央値の位置を取得または設定します。値の範囲は 0〜4096 です。

値: 中央値の位置です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setOpacity(double value) {#setOpacity-double-}
```
public abstract void setOpacity(double value)
```


不透明度を取得または設定します。

値: 不透明度です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

