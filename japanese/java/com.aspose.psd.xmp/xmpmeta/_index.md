---
title: "XmpMeta"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "xmpmeta を表します。"
type: docs
weight: 17
url: /ja/java/com.aspose.psd.xmp/xmpmeta/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

xmpmeta を表します。オプションです。この要素の目的は、RDF の他の非 XMP 用法を含む可能性のある一般的な XML テキスト内で XMP メタデータを識別することです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | XmpMeta クラスの新しいインスタンスを初期化します。 |
| [XmpMeta()](#XmpMeta--) | XmpMeta クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | 属性を追加します。 |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | 指定された XMP 要素を現在の要素に割り当てます。 |
| [clearAttributes()](#clearAttributes--) | すべての属性を削除します。 |
| [deepClone_internalized()](#deepClone-internalized--) | このインスタンスをクローンします。 |
| [equals(Object other)](#equals-java.lang.Object-) | 指定された  System.Object  がこのインスタンスと等しいかどうかを判断します。 |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Adobe Xmp ツールキットのバージョンを取得または設定します。 |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | 属性を取得します。 |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | XMP 値を XML 表現に変換します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | 現在のオブジェクトが同じ型の別のオブジェクトと等しいかどうかを示します。 |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.psd.xmp.XmpMeta-) | 現在のオブジェクトが同じ型の別のオブジェクトと等しいかどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Adobe Xmp ツールキットのバージョンを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


XmpMeta クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Adobe XMP ツールキットのバージョン。 |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


XmpMeta クラスの新しいインスタンスを初期化します。

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
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


指定された  System.Object  がこのインスタンスと等しいかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| その他 | java.lang.Object | このインスタンスと比較する System.Object。 |

**Returns:**
boolean - この指定された System.Object がこのインスタンスと等しい場合は true、そうでない場合は false。
### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Adobe Xmp ツールキットのバージョンを取得または設定します。

**Returns:**
java.lang.String
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
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP 値を XML 表現に変換します。

**Returns:**
java.lang.String - XMP 値を XML 表現に変換したものを返します。
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
### isEquals(XmpMeta other) {#isEquals-com.aspose.psd.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


現在のオブジェクトが同じ型の別のオブジェクトと等しいかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | このオブジェクトと比較するオブジェクト。 |

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




### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Adobe Xmp ツールキットのバージョンを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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

