---
title: "DublinCorePackage"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "Dublic Core スキーマを表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.xmp.schemas.dublincore/dublincorepackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class DublinCorePackage extends XmpPackage
```

Dublic Core スキーマを表します。

詳細については、http://dublincore.org/documents/usageguide/elements.shtml を参照してください。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [DublinCorePackage()](#DublinCorePackage--) | DublinCorePackage クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | 複合型名前空間を追加します。 |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | 文字列プロパティを追加します。 |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | 指定された XMP パッケージを現在のものに割り当てます。 |
| [clear()](#clear--) | このインスタンスをクリアします。 |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | パッケージを結合します。 |
| [containsKey(String key)](#containsKey-java.lang.String-) | 指定されたキーがキーを含むかどうかを判断します。 |
| [deepClone_internalized()](#deepClone-internalized--) | このインスタンスをクローンします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | XMP パッケージ内のキーを取得します。 |
| [getNamespaceUri()](#getNamespaceUri--) | 名前空間 URI を取得します。 |
| [getPrefix()](#getPrefix--) | プレフィックスを取得します。 |
| [getXmlNamespace()](#getXmlNamespace--) | XML 名前空間を取得します。 |
| [getXmlValue()](#getXmlValue--) | XMP 値を XML 表現に変換します。 |
| [get_Item(String key)](#get-Item-java.lang.String-) | 指定されたキーで Object を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | 指定されたキーの値を削除します。 |
| [setAuthor(String author)](#setAuthor-java.lang.String-) | 著者を追加します。 |
| [setAuthor(String[] author)](#setAuthor-java.lang.String---) | 著者を追加します。 |
| [setDescription(LangAlt desc)](#setDescription-com.aspose.psd.xmp.LangAlt-) | 説明を追加します。 |
| [setDescription(String desc)](#setDescription-java.lang.String-) | 説明を追加します。 |
| [setPublisher(String publisher)](#setPublisher-java.lang.String-) | 出版社を追加します。 |
| [setPublisher(String[] publisher)](#setPublisher-java.lang.String---) | 出版社を追加します。 |
| [setSubject(String subject)](#setSubject-java.lang.String-) | 主題を追加します。 |
| [setSubject(String[] subject)](#setSubject-java.lang.String---) | 主題を追加します。 |
| [setTitle(LangAlt title)](#setTitle-com.aspose.psd.xmp.LangAlt-) | 異なる言語向けの Dublin Core タイトルを追加します。 |
| [setTitle(String title)](#setTitle-java.lang.String-) | Dublin Core タイトルを追加します。 |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | 値を設定します。 |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | XMP のブール値を設定します。 |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | XMP の一意識別子を設定します。 |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | XMP のタイプ値を設定します。 |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 指定されたキーで  オブジェクト  を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DublinCorePackage() {#DublinCorePackage--}
```
public DublinCorePackage()
```


DublinCorePackage クラスの新しいインスタンスを初期化します。

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


複合型名前空間を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| typePrefix | java.lang.String | タイププレフィックスです。 |
| typeNamespaceUri | java.lang.String | タイプ名前空間 URI です。 |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


文字列プロパティを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | 追加された値で識別されるキーの文字列表現です。 |
| 値 | java.lang.String | 文字列値です。 |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


指定された XMP パッケージを現在のものに割り当てます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | XMP パッケージです。 |

### clear() {#clear--}
```
public void clear()
```


このインスタンスをクリアします。

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


パッケージを結合します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | 結合する他のパッケージです。 |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


指定されたキーがキーを含むかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | チェック対象のキーです。 |

**Returns:**
boolean - 指定されたキーがキーを含む場合は true を返します。
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


このインスタンスをクローンします。

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
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
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


XMP パッケージ内のキーを取得します。

値: XMP パッケージ内のキー。

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


名前空間 URI を取得します。

値: 名前空間 URI。

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


プレフィックスを取得します。

値: プレフィックス。

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


XML 名前空間を取得します。

値: XML 名前空間。

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP 値を XML 表現に変換します。

**Returns:**
java.lang.String - XMP 値を XML 表現に変換したものを返します。
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


指定されたキーで Object を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | 値を識別するキー。 |

**Returns:**
java.lang.Object - 指定されたキーに対応する  Object  を返します。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


コレクションを反復処理する列挙子を返します。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - コレクションを反復処理するために使用できる  T:System.Collections.Generic.IEnumerator1 です。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


指定されたキーの値を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | 削除された値で識別されるキーの文字列表現。 |

**Returns:**
boolean - 指定されたキーの値が削除された場合に true を返します。
### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


著者を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| author | java.lang.String | 著者です。 |

### setAuthor(String[] author) {#setAuthor-java.lang.String---}
```
public void setAuthor(String[] author)
```


著者を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| author | java.lang.String[] | 著者です。 |

### setDescription(LangAlt desc) {#setDescription-com.aspose.psd.xmp.LangAlt-}
```
public void setDescription(LangAlt desc)
```


説明を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| desc | [LangAlt](../../com.aspose.psd.xmp/langalt) | 説明です。 |

### setDescription(String desc) {#setDescription-java.lang.String-}
```
public void setDescription(String desc)
```


説明を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| desc | java.lang.String | 説明です。 |

### setPublisher(String publisher) {#setPublisher-java.lang.String-}
```
public void setPublisher(String publisher)
```


出版社を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| publisher | java.lang.String | 出版社です。 |

### setPublisher(String[] publisher) {#setPublisher-java.lang.String---}
```
public void setPublisher(String[] publisher)
```


出版社を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| publisher | java.lang.String[] | 出版社です。 |

### setSubject(String subject) {#setSubject-java.lang.String-}
```
public void setSubject(String subject)
```


主題を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| subject | java.lang.String | 主題です。 |

### setSubject(String[] subject) {#setSubject-java.lang.String---}
```
public void setSubject(String[] subject)
```


主題を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| subject | java.lang.String[] | 主題です。 |

### setTitle(LangAlt title) {#setTitle-com.aspose.psd.xmp.LangAlt-}
```
public void setTitle(LangAlt title)
```


異なる言語向けの Dublin Core タイトルを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| title | [LangAlt](../../com.aspose.psd.xmp/langalt) | LangAlt のインスタンス。 |

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Dublin Core タイトルを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| title | java.lang.String | タイトルです。 |

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | 追加された値で識別されるキーの文字列表現です。 |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | 追加する対象の値。 |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


XMP のブール値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | 設定された値で識別されるキーの文字列表現です。 |
| boolValue | java.lang.String | ブール値です。 |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


XMP の一意識別子を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | 設定された GUID 値で識別されるキーの文字列表現です。 |
| guid | java.lang.String | 一意の識別子です。 |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


XMP のタイプ値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | 設定された値で識別されるキーの文字列表現です。 |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | 設定する値です。 |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


指定されたキーで  オブジェクト  を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | 値を識別するキー。 |
| 値 | java.lang.Object | Object の値です。 |

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

