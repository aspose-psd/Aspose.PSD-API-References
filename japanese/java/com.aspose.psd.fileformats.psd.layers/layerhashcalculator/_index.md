---
title: "LayerHashCalculator"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "PSD レイヤー用ハッシュ計算機です。"
type: docs
weight: 20
url: /ja/java/com.aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Inheritance:**
java.lang.Object
```
public class LayerHashCalculator
```

PSD レイヤー用ハッシュ計算機。異なる PSD ファイル間で同一または異なるレイヤーを検出するために使用できます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [LayerHashCalculator(Layer layer)](#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-) | 新しい [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingHash()](#getBlendingHash--) | ブレンドハッシュを取得します。 |
| [getChannelsHash()](#getChannelsHash--) | チャンネルハッシュを取得します。 |
| [getClass()](#getClass--) |  |
| [getContentHash()](#getContentHash--) | コンテンツハッシュを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerHashCalculator(Layer layer) {#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public LayerHashCalculator(Layer layer)
```


新しい [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | レイヤーです。 |

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
### getBlendingHash() {#getBlendingHash--}
```
public final int getBlendingHash()
```


ブレンドハッシュを取得します。

**Returns:**
int - レイヤーブレンドオプションのユニークハッシュ
### getChannelsHash() {#getChannelsHash--}
```
public final int getChannelsHash()
```


チャンネルハッシュを取得します。

**Returns:**
int - すべてのレイヤーチャンネルのハッシュ
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentHash() {#getContentHash--}
```
public final int getContentHash()
```


コンテンツハッシュを取得します。

**Returns:**
int - レイヤーの重要パラメータのハッシュ。このハッシュはすべてのレイヤータイプで異なります
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

