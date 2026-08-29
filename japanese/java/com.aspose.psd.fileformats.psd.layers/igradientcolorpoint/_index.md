---
title: "IGradientColorPoint"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "塗り設定の基本インターフェイス"
type: docs
weight: 31
url: /ja/java/com.aspose.psd.fileformats.psd.layers/igradientcolorpoint/
---
```
public interface IGradientColorPoint
```

塗り設定の基本インターフェイス
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLocation()](#getLocation--) | 位置を取得または設定します。 |
| [getMedianPointLocation()](#getMedianPointLocation--) | 中央値の位置を取得または設定します。 |
| [getRawColor()](#getRawColor--) | raw の色を取得または設定します。 |
| [setLocation(int value)](#setLocation-int-) | 位置を取得または設定します。 |
| [setMedianPointLocation(int value)](#setMedianPointLocation-int-) | 中央値の位置を取得または設定します。 |
| [setRawColor(RawColor value)](#setRawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | raw の色を取得または設定します。 |
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
### getRawColor() {#getRawColor--}
```
public abstract RawColor getRawColor()
```


raw の色を取得または設定します。

値: raw の色です。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
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

### setRawColor(RawColor value) {#setRawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public abstract void setRawColor(RawColor value)
```


raw の色を取得または設定します。

値: raw の色です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

