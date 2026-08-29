---
title: "XmpRdfRoot"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "rdfRDF 要素を表します。"
type: docs
weight: 21
url: /ja/java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

rdf:RDF 要素を表します。単一の XMP パケットは単一の rdf:RDF XML 要素を使用してシリアライズされます。rdf:RDF 要素の内容は、0 個以上の rdf:Description 要素のみで構成されます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | XmpRdfRoot クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | 属性を追加します。 |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | 指定された XMP 要素を現在の要素に割り当てます。 |
| [clearAttributes()](#clearAttributes--) | すべての属性を削除します。 |
| [deepClone_internalized()](#deepClone-internalized--) | このインスタンスをクローンします。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された Object がこのインスタンスと等しいかどうかを判断します。 |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | 属性を取得します。 |
| [getClass()](#getClass--) |  |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | 特定のプレフィックスで名前空間 URI を取得します。 |
| [getXmlValue()](#getXmlValue--) | xmp 値を XML 表現に変換します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | 現在のオブジェクトが同じ型の別のオブジェクトと等しいかどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | プレフィックスで名前空間 URI を追加します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


XmpRdfRoot クラスの新しいインスタンスを初期化します。

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


属性を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性です。 |
| 値 | java.lang.String | 値です。 |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


指定された XMP 要素を現在の要素に割り当てます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | XMP 要素です。 |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


すべての属性を削除します。

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


このインスタンスをクローンします。

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定された Object がこのインスタンスと等しいかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較する Object。 |

**Returns:**
boolean - 指定された Object がこのインスタンスと等しい場合は true、そうでない場合は false。
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


属性を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性です。 |

**Returns:**
java.lang.String - 指定された属性名の属性を返します。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


特定のプレフィックスで名前空間 URI を取得します。プレフィックスは xmlns なしで開始できる場合があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| プレフィックス | java.lang.String | プレフィックスです。 |

**Returns:**
java.lang.String - パッケージ スキーマ URI を返します。
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


xmp 値を XML 表現に変換します。

**Returns:**
java.lang.String - XMP 値を XML 文字列に変換して返します。
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - このインスタンスのハッシュコード。ハッシュアルゴリズムやハッシュテーブルのようなデータ構造での使用に適しています。
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


現在のオブジェクトが同じ型の別のオブジェクトと等しいかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | このオブジェクトと比較するオブジェクト。 |

**Returns:**
boolean - 現在のオブジェクトが other パラメータと等しい場合は true、そうでない場合は false。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


プレフィックスで名前空間 URI を追加します。プレフィックスは xmlns なしで開始できる場合があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| プレフィックス | java.lang.String | プレフィックスです。 |
| namespaceUri | java.lang.String | パッケージ スキーマ URI。 |

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

