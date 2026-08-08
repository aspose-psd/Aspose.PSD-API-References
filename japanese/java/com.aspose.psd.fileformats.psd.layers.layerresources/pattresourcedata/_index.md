---
title: "PattResourceData"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "リソースのパターンデータを格納するクラスです。"
type: docs
weight: 67
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Inheritance:**
java.lang.Object
```
public final class PattResourceData
```

リソース [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) のパターンデータを格納するクラスです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PattResourceData()](#PattResourceData--) | 新しい [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createNewInstance_internalized()](#createNewInstance-internalized--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannelsCompressionMode_internalized()](#getChannelsCompressionMode-internalized--) | パターン\u2019s のチャンネルから取得した圧縮方式コードを返します。 |
| [getClass()](#getClass--) |  |
| [getDefaultPattern_internalized()](#getDefaultPattern-internalized--) | デフォルトのパターンデータを作成します。 |
| [getHeight()](#getHeight--) | 高さを取得します。 |
| [getImageMode()](#getImageMode--) | 画像モードを取得します。 |
| [getLength()](#getLength--) | パターンの長さを取得します。 |
| [getName()](#getName--) | 名前を取得または設定します。 |
| [getPatternData()](#getPatternData--) | パターン データを取得します。 |
| [getPatternDataArrayList_internalized()](#getPatternDataArrayList-internalized--) | メモリ配列リストです。 |
| [getPatternId()](#getPatternId--) | パターン識別子を取得または設定します。 |
| [getVersion()](#getVersion--) | バージョンを取得します。 |
| [getWidth()](#getWidth--) | 幅を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | パターンデータを保存します。 |
| [setHeight_internalized(short value)](#setHeight-internalized-short-) | 高さを取得します。 |
| [setImageMode_internalized(short value)](#setImageMode-internalized-short-) | 画像モードを取得します。 |
| [setIndexColorTable_internalized(byte[] value)](#setIndexColorTable-internalized-byte---) | インデックスカラー テーブルを取得または設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を取得または設定します。 |
| [setPattern(int[] pixels, Rectangle bounds)](#setPattern-int---com.aspose.psd.Rectangle-) | パターンのピクセルバッファとターゲットサイズを設定し、幅 ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / 高さ ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)) を更新し、デフォルト圧縮モード (0) を使用して保存用データを格納します。 |
| [setPatternDataArrayList_internalized(VirtualMemoryArrayList value)](#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-) | メモリ配列リストです。 |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | パターン識別子を取得または設定します。 |
| [setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)](#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-) | パターンのピクセルバッファとターゲットサイズを設定し、幅 ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / 高さ ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)) を更新し、指定された圧縮モードを使用して保存用データを格納します。 |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | バージョンを取得します。 |
| [setWidth_internalized(short value)](#setWidth-internalized-short-) | 幅を取得します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PattResourceData() {#PattResourceData--}
```
public PattResourceData()
```


新しい [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) クラスのインスタンスを初期化します。

### createNewInstance_internalized() {#createNewInstance-internalized--}
```
public static PattResourceData createNewInstance_internalized()
```




**Returns:**
[PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata)
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
### getChannelsCompressionMode_internalized() {#getChannelsCompressionMode-internalized--}
```
public final byte getChannelsCompressionMode_internalized()
```


パターン\u2019s のチャンネルから取得した圧縮方式コードを返します。

**Returns:**
byte - 圧縮コード: 0 \\u2014 生データ/非圧縮; >= 1 \\u2014 zip.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultPattern_internalized() {#getDefaultPattern-internalized--}
```
public static PixelsData getDefaultPattern_internalized()
```


デフォルトのパターンデータを作成します。

**Returns:**
[PixelsData](../../com.aspose.psd.pixelsdatamodels/pixelsdata) - The default pattern data.
### getHeight() {#getHeight--}
```
public final short getHeight()
```


高さを取得します。

値: 高さ。

**Returns:**
short
### getImageMode() {#getImageMode--}
```
public final short getImageMode()
```


画像モードを取得します。

値: 画像モード。

**Returns:**
short
### getLength() {#getLength--}
```
public final int getLength()
```


パターンの長さを取得します。

値: パターンの長さ。

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


名前を取得または設定します。

値: 名前です。

**Returns:**
java.lang.String
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


パターン データを取得します。

値: パターン データ。

**Returns:**
int[]
### getPatternDataArrayList_internalized() {#getPatternDataArrayList-internalized--}
```
public final VirtualMemoryArrayList getPatternDataArrayList_internalized()
```


メモリ配列リストです。

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


パターン識別子を取得または設定します。

値: パターン識別子。

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public final int getVersion()
```


バージョンを取得します。

値: バージョン。

**Returns:**
int
### getWidth() {#getWidth--}
```
public final short getWidth()
```


幅を取得します。

値: 幅。

**Returns:**
short
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




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


パターンデータを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |

### setHeight_internalized(short value) {#setHeight-internalized-short-}
```
public final void setHeight_internalized(short value)
```


高さを取得します。

値: 高さ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setImageMode_internalized(short value) {#setImageMode-internalized-short-}
```
public final void setImageMode_internalized(short value)
```


画像モードを取得します。

値: 画像モード。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setIndexColorTable_internalized(byte[] value) {#setIndexColorTable-internalized-byte---}
```
public final void setIndexColorTable_internalized(byte[] value)
```


インデックスカラー テーブルを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


名前を取得または設定します。

値: 名前です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPattern(int[] pixels, Rectangle bounds) {#setPattern-int---com.aspose.psd.Rectangle-}
```
public final void setPattern(int[] pixels, Rectangle bounds)
```


パターンのピクセルバッファとターゲットサイズを設定し、幅 ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / 高さ ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)) を更新し、デフォルト圧縮モード (0) を使用して保存用データを格納します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ピクセル | int[] | 0xAARRGGBB 形式の 32 ビットピクセル。 |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | パターンのピクセル境界。 |

### setPatternDataArrayList_internalized(VirtualMemoryArrayList value) {#setPatternDataArrayList-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList-}
```
public final void setPatternDataArrayList_internalized(VirtualMemoryArrayList value)
```


メモリ配列リストです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.internal.fileformats.psd.layers.layerresources.VirtualMemoryArrayList |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


パターン識別子を取得または設定します。

値: パターン識別子。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode) {#setPattern-internalized-int---com.aspose.psd.Rectangle-byte-}
```
public final void setPattern_internalized(int[] pixels, Rectangle bounds, byte compressionMode)
```


パターンのピクセルバッファとターゲットサイズを設定し、幅 ([.getWidth](../../null/\#getWidth)/[.setWidth(short)](../../null/\#setWidth-short-)) / 高さ ([.getHeight](../../null/\#getHeight)/[.setHeight(short)](../../null/\#setHeight-short-)) を更新し、指定された圧縮モードを使用して保存用データを格納します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ピクセル | int[] | 0xAARRGGBB 形式の 32 ビットピクセル。 |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | パターンのピクセル境界。 |
| compressionMode | byte | psd ファイル保存時にパターン データの圧縮を定義するために使用される圧縮モード。 |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


バージョンを取得します。

値: バージョン。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setWidth_internalized(short value) {#setWidth-internalized-short-}
```
public final void setWidth_internalized(short value)
```


幅を取得します。

値: 幅。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

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

