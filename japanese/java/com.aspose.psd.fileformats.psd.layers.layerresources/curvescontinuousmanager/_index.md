---
title: "CurvesContinuousManager"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "カーブ調整レイヤーのカーブを操作するマネージャー"
type: docs
weight: 24
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesContinuousManager extends CurvesManager
```

カーブ調整レイヤーのカーブを操作するマネージャー
## Constructors

| Constructor | 説明 |
| --- | --- |
| [CurvesContinuousManager(int maxChannelCount)](#CurvesContinuousManager-int-) | 新しい [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addCurvePoint(int channelIndex, byte x, byte y)](#addCurvePoint-int-byte-byte-) | 曲線のポイントを追加します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | リソースのバイトを取得します。 |
| [getClass()](#getClass--) |  |
| [getCurvePointByIndex(int channelIndex, int pointIndex)](#getCurvePointByIndex-int-int-) | インデックスで曲線ポイントを取得します。 |
| [getCurvePointCount(int channelIndex)](#getCurvePointCount-int-) | 曲線ポイントの数を取得します。 |
| [getMap_internalized()](#getMap-internalized--) | フィルタ処理用のマップを取得します。 |
| [getMaxChannelCount()](#getMaxChannelCount--) | 最大チャンネル数を取得します。 |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | バイトからデータをロードします。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeCurvePoint(int channelIndex, int pointIndex)](#removeCurvePoint-int-int-) | 曲線のポイントを削除します。 |
| [toString()](#toString--) |  |
| [updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)](#updateCurvePoint-int-int-byte-byte-) | 曲線のポイントを更新します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesContinuousManager(int maxChannelCount) {#CurvesContinuousManager-int-}
```
public CurvesContinuousManager(int maxChannelCount)
```


新しい [CurvesContinuousManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| maxChannelCount | int | 最大チャンネル数です。 |

### addCurvePoint(int channelIndex, byte x, byte y) {#addCurvePoint-int-byte-byte-}
```
public final void addCurvePoint(int channelIndex, byte x, byte y)
```


曲線のポイントを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelIndex | int | チャンネルのインデックスです。 |
| x | byte | X 座標です。 |
| y | byte | Y 座標です。 |

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
### getCurvePointByIndex(int channelIndex, int pointIndex) {#getCurvePointByIndex-int-int-}
```
public final Point getCurvePointByIndex(int channelIndex, int pointIndex)
```


インデックスで曲線ポイントを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelIndex | int | チャンネルのインデックスです。 |
| pointIndex | int | ポイントのインデックス。 |

**Returns:**
[Point](../../com.aspose.psd/point) - Curve point by index of channel
### getCurvePointCount(int channelIndex) {#getCurvePointCount-int-}
```
public final int getCurvePointCount(int channelIndex)
```


曲線ポイントの数を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelIndex | int | チャンネルのインデックスです。 |

**Returns:**
int - チャネル内のカーブポイントの数
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


フィルタ処理用のマップを取得します。

**Returns:**
byte[][] - チャネル処理用のマップ。
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


最大チャンネル数を取得します。

値: 最大チャネル数。

**Returns:**
int
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




### removeCurvePoint(int channelIndex, int pointIndex) {#removeCurvePoint-int-int-}
```
public final void removeCurvePoint(int channelIndex, int pointIndex)
```


曲線のポイントを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelIndex | int | チャンネルのインデックスです。 |
| pointIndex | int | ポイントのインデックス。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y) {#updateCurvePoint-int-int-byte-byte-}
```
public final void updateCurvePoint(int channelIndex, int pointIndex, byte x, byte y)
```


曲線のポイントを更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| channelIndex | int | チャンネルのインデックスです。 |
| pointIndex | int | ポイントのインデックス。 |
| x | byte | X 座標です。 |
| y | byte | Y 座標です。 |

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

