---
title: "UrlListResource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "URL リストリソース"
type: docs
weight: 40
url: /ja/java/com.aspose.psd.fileformats.psd.resources/urllistresource/
---

**Inheritance:**
java.lang.Object、[com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class UrlListResource extends ResourceBlock
```

URL リストリソース
## Constructors

| Constructor | 説明 |
| --- | --- |
| [UrlListResource()](#UrlListResource--) | 新しいインスタンスを初期化します [UrlListResource](../../com.aspose.psd.fileformats.psd.resources/urllistresource) クラス。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | ImageReady のリソース署名です。 |
| [ResouceBlockSignature](#ResouceBlockSignature) | 通常の Photoshop リソース署名です。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | カウントを取得または設定します。 |
| [getDataSize()](#getDataSize--) | リソース データのサイズ（バイト）を取得します。 |
| [getID()](#getID--) | リソースの一意識別子を取得または設定します。 |
| [getIds()](#getIds--) | 取得または設定します ids。 |
| [getLongs()](#getLongs--) | 取得または設定します longs。 |
| [getMinimalVersion()](#getMinimalVersion--) | 最小限の必要な PSD バージョンを取得します。 |
| [getName()](#getName--) | リソース名を取得または設定します。 |
| [getSignature()](#getSignature--) | リソース署名を取得します。 |
| [getSize()](#getSize--) | データを含むリソースブロックのサイズ（バイト単位）を取得します。 |
| [getTexts()](#getTexts--) | 取得または設定します texts。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | リソースブロックを指定されたストリームに保存します。 |
| [setCount(int value)](#setCount-int-) | カウントを取得または設定します。 |
| [setID(short value)](#setID-short-) | リソースの一意識別子を取得または設定します。 |
| [setIds(int[] value)](#setIds-int---) | 取得または設定します ids。 |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | レイヤーとマスク情報を取得または設定します。 |
| [setLongs(int[] value)](#setLongs-int---) | 取得または設定します longs。 |
| [setName(String value)](#setName-java.lang.String-) | リソース名を取得または設定します。 |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | リソースブロックの状態を取得または設定します。 |
| [setTexts(String[] value)](#setTexts-java.lang.String---) | 取得または設定します texts。 |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | リソースの値を検証します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### UrlListResource() {#UrlListResource--}
```
public UrlListResource()
```


新しいインスタンスを初期化します [UrlListResource](../../com.aspose.psd.fileformats.psd.resources/urllistresource) クラス。

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public final int getCount()
```


カウントを取得または設定します。

値: カウント。

**Returns:**
int
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


リソース データのサイズ（バイト）を取得します。

値: リソースデータサイズ。

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
### getIds() {#getIds--}
```
public final int[] getIds()
```


取得または設定します ids。

値: ids。

**Returns:**
int[]
### getLongs() {#getLongs--}
```
public final int[] getLongs()
```


取得または設定します longs。

値: longs。

**Returns:**
int[]
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


最小限の必要な PSD バージョンを取得します。

値: 最小 PSD バージョン。

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
### getTexts() {#getTexts--}
```
public final String[] getTexts()
```


取得または設定します texts。

値: texts。

**Returns:**
java.lang.String[]
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

### setCount(int value) {#setCount-int-}
```
public final void setCount(int value)
```


カウントを取得または設定します。

値: カウント。

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

### setIds(int[] value) {#setIds-int---}
```
public final void setIds(int[] value)
```


取得または設定します ids。

値: ids。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] |  |

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

### setLongs(int[] value) {#setLongs-int---}
```
public final void setLongs(int[] value)
```


取得または設定します longs。

値: longs。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] |  |

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

### setTexts(String[] value) {#setTexts-java.lang.String---}
```
public final void setTexts(String[] value)
```


取得または設定します texts。

値: texts。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String[] |  |

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

