---
title: "チャンネル情報"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "チャンネル情報です。"
type: docs
weight: 13
url: /ja/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

チャンネル情報です。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | ユーザー（ラスタ）マスクチャンネルID。 |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | ショート（ラスタまたはベクター）マスクチャンネルID。 |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | アルファチャンネルID |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | チャンネルデータを圧縮します |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | 指定されたチャンネル情報をクローンします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | チャンネルのビット深度を取得します。 |
| [getChannelID()](#getChannelID--) | チャンネルIDを取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | 圧縮方法を取得または設定します。 |
| [getData_internalized()](#getData-internalized--) | チャンネルデータを取得または設定します。 |
| [getLength()](#getLength--) | チャンネルの長さ（バイト）を取得します。 |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | PSDのバージョンを取得します |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | 非圧縮データを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | チャンネルがショートマスクかどうかを取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | チャンネルデータを保存します。 |
| [setChannelID(short value)](#setChannelID-short-) | チャンネルIDを取得または設定します。 |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | 圧縮データを設定します。 |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | 圧縮方法を取得または設定します。 |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | 圧縮データを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 圧縮方法 | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


ユーザー（ラスタ）マスクチャンネルID。（レイヤーがベクターとラスタの両方のマスクを持つ場合）

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


ショート（ラスタまたはベクター）マスクチャンネルID。（レイヤーがベクターまたはラスタのいずれか一方のマスクのみを持ち、両方は持たない場合）

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


アルファチャンネルID

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


チャンネルデータを圧縮します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 生データ | byte[] | 圧縮用の生データ |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | レイヤーの境界 |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | レイヤーマスクの境界 |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 圧縮データ | byte[] |  |
| 圧縮方法 | short |  |
| 幅 | int |  |
| 高さ | int |  |
| ヘッダー | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 圧縮方法 | short |  |
| ヘッダー | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


指定されたチャンネル情報をクローンします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | 情報。 |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - 複製されたレイヤーマスク。
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
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


チャンネルのビット深度を取得します。

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


チャンネルIDを取得または設定します。

値: チャネル ID。

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


圧縮方法を取得または設定します。

値: 圧縮方法。

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


チャンネルデータを取得または設定します。

値: チャネル データ。

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


チャンネルの長さ（バイト）を取得します。

値: 長さ。

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


PSDのバージョンを取得します

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


非圧縮データを取得します。

**Returns:**
byte[] -
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isShortMaskChannel_internalized() {#isShortMaskChannel-internalized--}
```
public final boolean isShortMaskChannel_internalized()
```


チャンネルがショートマスクかどうかを取得します。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveChannelData_internalized(StreamContainer streamContainer) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


チャンネルデータを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |
| is32BitColor | boolean | 色が32ビットモードの場合は true |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


チャンネルIDを取得または設定します。

値: チャネル ID。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


圧縮データを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 圧縮データ | byte[] | 圧縮されたデータ。 |
| channelWidth | int | チャネルの幅。 |
| channelHeight | int | チャネルの高さ。 |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


圧縮方法を取得または設定します。

値: 圧縮方法。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


圧縮データを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 生データ | byte[] | 生データ。 |
| imageSize | [Size](../../com.aspose.psd/size) | 画像のサイズ |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | 現在の channelData の境界。画像が大きい場合、処理中に分割され、currentBounds は imageBounds と等しくありません。 |

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

