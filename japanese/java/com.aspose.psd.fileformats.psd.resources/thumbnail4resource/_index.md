---
title: "Thumbnail4Resource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "psd 4.0 用のサムネイルリソースを表します。"
type: docs
weight: 34
url: /ja/java/com.aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock), [com.aspose.psd.fileformats.psd.resources.ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource)
```
public final class Thumbnail4Resource extends ThumbnailResource
```

psd 4.0 用のサムネイルリソースを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Thumbnail4Resource()](#Thumbnail4Resource--) | [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource) クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | ImageReady のリソース署名です。 |
| [ResouceBlockSignature](#ResouceBlockSignature) | 通常の Photoshop リソース署名です。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | ビットピクセルを取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | リソース データのサイズ（バイト）を取得します。 |
| [getFormat()](#getFormat--) | サムネイル データ形式を取得または設定します。 |
| [getHeight()](#getHeight--) | サムネイルの高さ（ピクセル単位）を取得または設定します。 |
| [getID()](#getID--) | リソースの一意識別子を取得または設定します。 |
| [getJpegOptions()](#getJpegOptions--) | JPEG オプションを取得または設定します。 |
| [getMinimalVersion()](#getMinimalVersion--) | 最小限必要な psd バージョンを取得します。 |
| [getName()](#getName--) | リソース名を取得または設定します。 |
| [getPlanesCount()](#getPlanesCount--) | プレーン数を取得または設定します。 |
| [getSignature()](#getSignature--) | リソース署名を取得します。 |
| [getSize()](#getSize--) | データを含むリソースブロックのサイズ（バイト単位）を取得します。 |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | 圧縮後のサイズを取得または設定します。 |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | 32 ビット ARGB サムネイル データを取得または設定します。 |
| [getThumbnailData()](#getThumbnailData--) | サムネイル データを取得または設定します。 |
| [getTotalSize()](#getTotalSize--) | 総データサイズを取得します。 |
| [getWidth()](#getWidth--) | サムネイルの幅（ピクセル単位）を取得または設定します。 |
| [getWidthBytes()](#getWidthBytes--) | 行幅（バイト単位）を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | リソースブロックを指定されたストリームに保存します。 |
| [setBitsPixel(short value)](#setBitsPixel-short-) | ビットピクセルを取得または設定します。 |
| [setFormat(int value)](#setFormat-int-) | サムネイル データ形式を取得または設定します。 |
| [setHeight(int value)](#setHeight-int-) | サムネイルの高さ（ピクセル単位）を取得または設定します。 |
| [setID(short value)](#setID-short-) | リソースの一意識別子を取得または設定します。 |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | JPEG オプションを取得または設定します。 |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | レイヤーとマスク情報を取得または設定します。 |
| [setName(String value)](#setName-java.lang.String-) | リソース名を取得または設定します。 |
| [setPlanesCount(short value)](#setPlanesCount-short-) | プレーン数を取得または設定します。 |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | リソースブロックの状態を取得または設定します。 |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | 32 ビット ARGB サムネイル データを取得または設定します。 |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | サムネイル データを取得または設定します。 |
| [setWidth(int value)](#setWidth-int-) | サムネイルの幅（ピクセル単位）を取得または設定します。 |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | リソースの値を検証します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Thumbnail4Resource() {#Thumbnail4Resource--}
```
public Thumbnail4Resource()
```


[Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource) クラスの新しいインスタンスを初期化します。

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


ImageReady のリソース署名です。

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


通常の Photoshop リソース署名です。

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
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


ビットピクセルを取得または設定します。

値: サムネイル ビットピクセル。

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


リソース データのサイズ（バイト）を取得します。

値: リソースデータサイズ。

**Returns:**
int
### getFormat() {#getFormat--}
```
public final int getFormat()
```


サムネイル データ形式を取得または設定します。

値: サムネイル データ形式。

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


サムネイルの高さ（ピクセル単位）を取得または設定します。

値: サムネイルの高さ。

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


リソースの一意識別子を取得または設定します。

値: リソースの一意識別子。

**Returns:**
short
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


JPEG オプションを取得または設定します。サムネイルリソースが JPEG ファイル形式でのみ保存される場合に適しています。このオプションは RAW 形式が定義されている場合には効果がありません。

値: JPEG オプション。

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


最小限必要な psd バージョンを取得します。

値: 最小 psd バージョン。

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


リソース名を取得または設定します。Pascal 文字列で、サイズが偶数になるようにパディングされます（null 名は 0 のバイト2つで構成されます）。

値: リソース名。

**Returns:**
java.lang.String
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


プレーン数を取得または設定します。

値: サムネイル平面数。

**Returns:**
short
### getSignature() {#getSignature--}
```
public final int getSignature()
```


リソース署名を取得します。常に '8BIM' である必要があります。

値: リソース署名。

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


データを含むリソースブロックのサイズ（バイト単位）を取得します。

値: リソースブロックサイズ。

**Returns:**
int
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


圧縮後のサイズを取得または設定します。整合性チェックに使用されます。

値: 圧縮後のサイズ。

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


32 ビット ARGB サムネイル データを取得または設定します。

値: 32 ビット ARGB サムネイルデータ。

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


サムネイル データを取得または設定します。

値: サムネイルデータ。

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


総データサイズを取得します。

値: 総データサイズ。

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


サムネイルの幅（ピクセル単位）を取得または設定します。

値: サムネイルの幅。

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


行幅（バイト単位）を取得します。

値: 行幅（バイト単位）。

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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


リソースブロックを指定されたストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | リソースブロックを保存するストリーム。 |

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


ビットピクセルを取得または設定します。

値: サムネイル ビットピクセル。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


サムネイル データ形式を取得または設定します。

値: サムネイル データ形式。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


サムネイルの高さ（ピクセル単位）を取得または設定します。

値: サムネイルの高さ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


リソースの一意識別子を取得または設定します。

値: リソースの一意識別子。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


JPEG オプションを取得または設定します。サムネイルリソースが JPEG ファイル形式でのみ保存される場合に適しています。このオプションは RAW 形式が定義されている場合には効果がありません。

値: JPEG オプション。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


レイヤーとマスク情報を取得または設定します。

値: レイヤーとマスク情報。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


リソース名を取得または設定します。Pascal 文字列で、サイズが偶数になるようにパディングされます（null 名は 0 のバイト2つで構成されます）。

値: リソース名。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


プレーン数を取得または設定します。

値: サムネイル平面数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 署名 | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


リソースブロックの状態を取得または設定します。

値: リソースブロックの状態。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


32 ビット ARGB サムネイル データを取得または設定します。

値: 32 ビット ARGB サムネイルデータ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


サムネイル データを取得または設定します。

値: サムネイルデータ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


サムネイルの幅（ピクセル単位）を取得または設定します。

値: サムネイルの幅。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


リソースの値を検証します。

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

