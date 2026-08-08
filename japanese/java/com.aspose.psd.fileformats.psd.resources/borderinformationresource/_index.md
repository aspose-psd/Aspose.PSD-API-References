---
title: "BorderInformationResource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "画像印刷設定の境界情報を含むリソースです。"
type: docs
weight: 12
url: /ja/java/com.aspose.psd.fileformats.psd.resources/borderinformationresource/
---

**Inheritance:**
java.lang.Object、[com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class BorderInformationResource extends ResourceBlock
```

画像印刷設定の境界情報を含むリソースです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [BorderInformationResource()](#BorderInformationResource--) | 新しい [BorderInformationResource](../../com.aspose.psd.fileformats.psd.resources/borderinformationresource) クラスのインスタンスを初期化します。 |
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
| [getDataSize()](#getDataSize--) | リソース データのサイズ（バイト）を取得します。 |
| [getID()](#getID--) | リソースの一意識別子を取得または設定します。 |
| [getMinimalVersion()](#getMinimalVersion--) | 最小限の必要な PSD バージョンを取得します。 |
| [getName()](#getName--) | リソース名を取得または設定します。 |
| [getSignature()](#getSignature--) | リソース署名を取得します。 |
| [getSize()](#getSize--) | データを含むリソースブロックのサイズ（バイト単位）を取得します。 |
| [getUnit()](#getUnit--) | 境界単位を取得または設定します。 |
| [getWidth()](#getWidth--) | 境界幅を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | リソースブロックを指定されたストリームに保存します。 |
| [setID(short value)](#setID-short-) | リソースの一意識別子を取得または設定します。 |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | レイヤーとマスク情報を取得または設定します。 |
| [setName(String value)](#setName-java.lang.String-) | リソース名を取得または設定します。 |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | リソースブロックの状態を取得または設定します。 |
| [setUnit(int value)](#setUnit-int-) | 境界単位を取得または設定します。 |
| [setWidth(double value)](#setWidth-double-) | 境界幅を取得または設定します。 |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | リソースの値を検証します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BorderInformationResource() {#BorderInformationResource--}
```
public BorderInformationResource()
```


新しい [BorderInformationResource](../../com.aspose.psd.fileformats.psd.resources/borderinformationresource) クラスのインスタンスを初期化します。

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
### getUnit() {#getUnit--}
```
public final int getUnit()
```


境界単位を取得または設定します。

**Returns:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```


境界幅を取得または設定します。

**Returns:**
double
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

### setUnit(int value) {#setUnit-int-}
```
public final void setUnit(int value)
```


境界単位を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


境界幅を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

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

