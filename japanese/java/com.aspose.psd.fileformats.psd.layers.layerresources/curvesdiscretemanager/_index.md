---
title: "CurvesDiscreteManager"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ピクセルマップを操作する Curves Adjustment Layer のマネージャー"
type: docs
weight: 25
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

カーブ調整レイヤーのピクセルマップを操作するマネージャー
## Constructors

| Constructor | 説明 |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | 新しいインスタンスを初期化します [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) クラス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | リソースのバイトを取得します。 |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | フィルタ処理用のマップを取得します。 |
| [getMaxChannelCount()](#getMaxChannelCount--) | 最大チャンネル数を取得します。 |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | 位置の値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | バイトからデータをロードします。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | 位置のデフォルト値に設定します。 |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | 位置の値を設定します。 |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | チャネル全体の値を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


新しいインスタンスを初期化します [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) クラス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| maxChannelCount | int | 最大チャンネル数です。 |

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
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


リソースのバイトを取得します。

**Returns:**
byte[] - CurvResource を構成するバイト
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


フィルタ処理用のマップを取得します。

**Returns:**
byte[][] - 変換マップ
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


最大チャンネル数を取得します。

値: 最大チャネル数。

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


位置の値を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelIndex | int | チャンネルのインデックスです。 |
| position | byte | 位置。 |

**Returns:**
byte - 位置によるカーブの値
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadFromBytes_internalized(byte[] bytes) {#loadFromBytes-internalized-byte---}
```
public void loadFromBytes_internalized(byte[] bytes)
```


バイトからデータをロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| バイト | byte[] | バイト。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setToDefaultValueInPosition(int channelIndex, byte position) {#setToDefaultValueInPosition-int-byte-}
```
public final void setToDefaultValueInPosition(int channelIndex, byte position)
```


位置のデフォルト値に設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelIndex | int | チャンネルのインデックスです。 |
| position | byte | 位置。 |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


位置の値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelIndex | int | チャンネルのインデックスです。 |
| position | byte | 位置。 |
| 値 | byte | 値です。 |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


チャネル全体の値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelIndex | int | チャンネルのインデックスです。 |
| channelValue | byte[] | チャネルの値です。 |

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

