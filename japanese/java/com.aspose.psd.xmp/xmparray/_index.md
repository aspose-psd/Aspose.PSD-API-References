---
title: "XmpArray"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "XmpPackage 内の Xmp Array を表します。"
type: docs
weight: 12
url: /ja/java/com.aspose.psd.xmp/xmparray/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

XmpPackage 内の Xmp Array を表します。todo: 配列には複雑なデータが含まれる可能性があります。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | XmpArray クラスの新しいインスタンスを初期化します。 |
| [XmpArray(int type)](#XmpArray-int-) | XmpArray クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addElement_internalized(XmpPackage element)](#addElement-internalized-com.aspose.psd.xmp.XmpPackage-) | 新しい項目を追加します。 |
| [addItem(String item)](#addItem-java.lang.String-) | 新しい項目を追加します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements_internalized()](#getElements-internalized--) | [XmpArray](../../com.aspose.psd.xmparray) 内の値の配列を取得します。 |
| [getValues()](#getValues--) | XmpArray 内の値の配列を取得します。 |
| [getXmlValue()](#getXmlValue--) | XMP 値を XML 表現に変換します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | このインスタンスを表す  System.String  を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


XmpArray クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 型 | int | 配列の型。 |
| アイテム | java.lang.String[] | 項目リスト。 |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


XmpArray クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 型 | int | 配列の型。 |

### addElement_internalized(XmpPackage element) {#addElement-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public final void addElement_internalized(XmpPackage element)
```


新しい項目を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | 項目リストに追加される要素。 |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


新しい項目を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | java.lang.String | 項目リストに追加される項目。 |

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
### getElements_internalized() {#getElements-internalized--}
```
public final XmpPackage[] getElements_internalized()
```


[XmpArray](../../com.aspose.psd.xmparray) 内の値の配列を取得します。

**Returns:**
com.aspose.psd.xmp.XmpPackage[]
### getValues() {#getValues--}
```
public String[] getValues()
```


XmpArray 内の値の配列を取得します。

**Returns:**
java.lang.String[]
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP 値を XML 表現に変換します。

**Returns:**
java.lang.String - XMP 値を XML 表現に変換したものを返します。
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


このインスタンスを表す  System.String  を返します。

**Returns:**
java.lang.String - このインスタンスを表す System.String。
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

