---
title: "XmpHeaderPi"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "XMP ヘッダーの処理指示を表します。"
type: docs
weight: 16
url: /ja/java/com.aspose.psd.xmp/xmpheaderpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

XMP ヘッダーの処理指示を表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | 新しい  XmpHeaderPi  クラスのインスタンスを初期化します。 |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | 新しい  XmpHeaderPi  クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | このインスタンスをクローンします。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された  System.Object  がこのインスタンスと等しいかどうかを判断します。 |
| [getClass()](#getClass--) |  |
| [getGuid()](#getGuid--) | ヘッダー GUID を表します。 |
| [getXmlValue()](#getXmlValue--) | XMP 値を XML 表現に変換します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.psd.xmp.XmpHeaderPi-) | 現在のオブジェクトが同じ型の別のオブジェクトと等しいかどうかを示します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(String value)](#setGuid-java.lang.String-) | ヘッダー GUID を表します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


新しい  XmpHeaderPi  クラスのインスタンスを初期化します。

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


新しい  XmpHeaderPi  クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| guid | java.lang.String | 一意の識別子です。 |

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpHeaderPi deepClone_internalized()
```


このインスタンスをクローンします。

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定された  System.Object  がこのインスタンスと等しいかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較する System.Object。 |

**Returns:**
boolean - この指定された System.Object がこのインスタンスと等しい場合は true、そうでない場合は false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGuid() {#getGuid--}
```
public String getGuid()
```


ヘッダー GUID を表します。

ヘッダー PI のテキストには GUID が含まれており、データストリームに偶然現れる可能性は低くなります。

**Returns:**
java.lang.String
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
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.psd.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


現在のオブジェクトが同じ型の別のオブジェクトと等しいかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | このオブジェクトと比較するオブジェクト。 |

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




### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


ヘッダー GUID を表します。

ヘッダー PI のテキストには GUID が含まれており、データストリームに偶然現れる可能性は低くなります。

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

