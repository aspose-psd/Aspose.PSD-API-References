---
title: "XmpPacketWrapper"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ヘッダーとトレーラーを含むシリアライズされた xmp パッケージを含みます。"
type: docs
weight: 20
url: /ja/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

ヘッダーとトレーラーを含むシリアライズされた xmp パッケージを含みます。

XML 処理指示 (PI) のペアで構成されたラッパーは、rdf:RDF 要素の周囲に配置されることがあります。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | 新しい  XmpPacketWrapper  クラスのインスタンスを初期化します。 |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | 新しい  XmpPacketWrapper  クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | パッケージを追加します。 |
| [clearPackages()](#clearPackages--) | XMP 内のすべての XmpPackage を削除します。 |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | xmp ラッパーにパッケージが存在するかどうかを判定します。 |
| [deepClone_internalized()](#deepClone-internalized--) | このインスタンスをクローンします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | ヘッダーの処理指示を取得します。 |
| [getMeta()](#getMeta--) | XMP メタを取得します。 |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | 名前空間 URI によるパッケージを取得します。 |
| [getPackages()](#getPackages--) | XMP 内の XmpPackage 配列を取得します。 |
| [getPackagesCount()](#getPackagesCount--) | XMP 構造内のパッケージ数を取得します。 |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | ルート RDF 要素を取得します。 |
| [getTrailerPi()](#getTrailerPi--) | トレーラーの処理指示を取得します。 |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | XMP 値を XML 表現に変換します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | XMP パッケージを削除します。 |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | ヘッダーの処理指示を設定します。 |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | XMP メタを設定します。 |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | ルート RDF 要素を設定します。 |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | トレーラーの処理指示を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


新しい  XmpPacketWrapper  クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | 処理指示の XMP ヘッダーです。 |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | 処理指示の XMP トレーラーです。 |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | XMP メタデータです。 |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


新しい  XmpPacketWrapper  クラスのインスタンスを初期化します。

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


パッケージを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | パッケージです。 |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


XMP 内のすべての XmpPackage を削除します。

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


xmp ラッパーにパッケージが存在するかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| namespaceUri | java.lang.String | パッケージ スキーマ URI。 |

**Returns:**
boolean - 指定された名前空間 URI を持つパッケージが XMP ラッパーに存在する場合、true を返します。
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


このインスタンスをクローンします。

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
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
### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


ヘッダーの処理指示を取得します。

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


XMP メタを取得します。オプション。

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


名前空間 URI によるパッケージを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| namespaceUri | java.lang.String | パッケージ スキーマ URIです。 |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


XMP 内の XmpPackage 配列を取得します。

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - XMP 内の XmpPackage 配列です。
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


XMP 構造内のパッケージ数を取得します。

**Returns:**
int - XMP 構造内のパッケージ数です。
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


ルート RDF 要素を取得します。

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


トレーラーの処理指示を取得します。

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


XMP 値を XML 表現に変換します。

**Returns:**
java.lang.String - 変換された XMP 値を XML に返します。
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




### removePackage(XmpPackage package_) {#removePackage-com.aspose.psd.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


XMP パッケージを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | パッケージです。 |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


ヘッダーの処理指示を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | ヘッダー処理指示。 |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


XMP メタを設定します。オプションです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | XMP メタです。オプションです。 |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


ルート RDF 要素を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | RDF ルート要素です。 |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


トレーラーの処理指示を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | トレーラ処理指示。 |

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

