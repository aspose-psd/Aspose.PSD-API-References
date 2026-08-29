---
title: "GradientColorPoint"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "グラデーションカラー点。"
type: docs
weight: 13
url: /ja/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint)
```
public class GradientColorPoint implements IGradientColorPoint
```

グラデーションカラー点。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [GradientColorPoint()](#GradientColorPoint--) | 新しい [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) クラスのインスタンスを初期化します。 |
| [GradientColorPoint(Color color, int location, int medianPointLocation)](#GradientColorPoint-com.aspose.psd.Color-int-int-) | 新しい [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [create_internalized(GradientColorPointEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.GradientColorPointEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | 色が従うモード |
| [getLocation()](#getLocation--) | グラデーション上のポイント位置を取得または設定します。 |
| [getMedianPointLocation()](#getMedianPointLocation--) | 中央値グラデーションポイントの位置を取得または設定します。 |
| [getRawColor()](#getRawColor--) | raw の色を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorMode(short value)](#setColorMode-short-) | 色が従うモード |
| [setLocation(int value)](#setLocation-int-) | グラデーション上のポイント位置を取得または設定します。 |
| [setMedianPointLocation(int value)](#setMedianPointLocation-int-) | 中央値グラデーションポイントの位置を取得または設定します。 |
| [setRawColor(RawColor value)](#setRawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | raw の色を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientColorPoint() {#GradientColorPoint--}
```
public GradientColorPoint()
```


新しい [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) クラスのインスタンスを初期化します。

### GradientColorPoint(Color color, int location, int medianPointLocation) {#GradientColorPoint-com.aspose.psd.Color-int-int-}
```
public GradientColorPoint(Color color, int location, int medianPointLocation)
```


新しい [GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | グラデーション上のカラーポイント。 |
| 位置 | int | グラデーション上のカラーポイントの位置です。 |
| medianPointLocation | int | 中央値グラデーションポイントの位置です。 |

### create_internalized(GradientColorPointEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.GradientColorPointEntity-}
```
public static GradientColorPoint create_internalized(GradientColorPointEntity entity)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| エンティティ | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.GradientColorPointEntity |  |

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


色が従うモード

**Returns:**
short
### getLocation() {#getLocation--}
```
public final int getLocation()
```


グラデーション上のポイント位置を取得または設定します。

値: 位置です。

**Returns:**
int
### getMedianPointLocation() {#getMedianPointLocation--}
```
public final int getMedianPointLocation()
```


中央値グラデーションポイントの位置を取得または設定します。

値: 中央値の位置です。

**Returns:**
int
### getRawColor() {#getRawColor--}
```
public final RawColor getRawColor()
```


raw の色を取得または設定します。

値: raw の色です。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
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




### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


色が従うモード

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setLocation(int value) {#setLocation-int-}
```
public final void setLocation(int value)
```


グラデーション上のポイント位置を取得または設定します。

値: 位置です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMedianPointLocation(int value) {#setMedianPointLocation-int-}
```
public final void setMedianPointLocation(int value)
```


中央値グラデーションポイントの位置を取得または設定します。

値: 中央値の位置です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setRawColor(RawColor value) {#setRawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setRawColor(RawColor value)
```


raw の色を取得または設定します。

値: raw の色です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

