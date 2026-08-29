---
title: "PixelsData"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "画像ピクセルデータとその境界を格納するクラスです。"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.pixelsdatamodels/pixelsdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public final class PixelsData implements System.ICloneable
```

画像ピクセルデータとその境界を格納するクラスです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PixelsData()](#PixelsData--) | 新しい [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) クラスのインスタンスを初期化します。 |
| [PixelsData(int[] pixels, Rectangle bounds)](#PixelsData-int---com.aspose.psd.Rectangle-) | 新しい [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createLoader_internalized()](#createLoader-internalized--) | [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) の現在のインスタンス用に PixelsDataLoader インスタンスを作成します。 |
| [createSaver_internalized()](#createSaver-internalized--) | [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) の現在のインスタンス用に PixelsDataSaver インスタンスを作成します。 |
| [deepClone()](#deepClone--) | インスタンスの完全なコピーを作成します |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | ピクセルデータの境界を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getPixels()](#getPixels--) | ピクセルデータを取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | ピクセルデータの境界を取得または設定します。 |
| [setPixels(int[] value)](#setPixels-int---) | ピクセルデータを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PixelsData() {#PixelsData--}
```
public PixelsData()
```


新しい [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) クラスのインスタンスを初期化します。

### PixelsData(int[] pixels, Rectangle bounds) {#PixelsData-int---com.aspose.psd.Rectangle-}
```
public PixelsData(int[] pixels, Rectangle bounds)
```


新しい [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ピクセル | int[] | ピクセルデータ。 |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | ピクセルの境界矩形です。 |

### createLoader_internalized() {#createLoader-internalized--}
```
public final IRasterImageArgb32PixelLoader createLoader_internalized()
```


[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) の現在のインスタンス用に PixelsDataLoader インスタンスを作成します。

**Returns:**
[IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) - The new instance of PixelsDataLoader base on current instance of [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata).
### createSaver_internalized() {#createSaver-internalized--}
```
public final IPixelsSaver createSaver_internalized()
```


[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) の現在のインスタンス用に PixelsDataSaver インスタンスを作成します。

**Returns:**
com.aspose.internal.IPixelsSaver - 現在の [PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) インスタンスに基づく PixelsDataSaver の新しいインスタンス。
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


インスタンスの完全なコピーを作成します

**Returns:**
java.lang.Object - インスタンスのコピーです。
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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


ピクセルデータの境界を取得または設定します。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPixels() {#getPixels--}
```
public final int[] getPixels()
```


ピクセルデータを取得または設定します。

**Returns:**
int[]
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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


ピクセルデータの境界を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setPixels(int[] value) {#setPixels-int---}
```
public final void setPixels(int[] value)
```


ピクセルデータを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] |  |

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

