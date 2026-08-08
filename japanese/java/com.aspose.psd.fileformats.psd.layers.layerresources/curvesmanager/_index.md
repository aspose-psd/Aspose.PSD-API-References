---
title: "CurvesManager"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "CurvResource を管理する基底クラス"
type: docs
weight: 26
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class CurvesManager
```

CurvResource を管理する基底クラス
## Constructors

| Constructor | 説明 |
| --- | --- |
| [CurvesManager(int maxChannelCount)](#CurvesManager-int-) | 新しい [CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | リソースのバイトを取得します。 |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | フィルタ処理用のマップを取得します。 |
| [getMaxChannelCount()](#getMaxChannelCount--) | 最大チャンネル数を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesManager(int maxChannelCount) {#CurvesManager-int-}
```
public CurvesManager(int maxChannelCount)
```


新しい [CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) クラスのインスタンスを初期化します。

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
public abstract byte[][] getMap_internalized()
```


フィルタ処理用のマップを取得します。

**Returns:**
byte[][] - チャンネル処理用のマップ
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

