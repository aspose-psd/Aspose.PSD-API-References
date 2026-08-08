---
title: "XmpMediaManagementPackage"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "XMP Media Management 名前空間を表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class XmpMediaManagementPackage extends XmpPackage
```

XMP Media Management 名前空間を表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage--) | XmpMediaManagementPackage クラスの新しいインスタンスを初期化します。 |
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
| [setDerivedFrom(ResourceRef resourceRef)](#setDerivedFrom-com.aspose.psd.xmp.types.complex.resourceref.ResourceRef-) | 派生元を設定します。 |
| [setDocumentId(String guid)](#setDocumentId-java.lang.String-) | ドキュメント識別子を設定します。 |
| [setDocumentId(UUID guid)](#setDocumentId-java.util.UUID-) | ドキュメント識別子を設定します。 |
| [setDocumentId_internalized(System.Guid guid)](#setDocumentId-internalized-com.aspose.ms.System.Guid-) |  |
| [setInstanceId(String guid)](#setInstanceId-java.lang.String-) | インスタンス ID を設定します。 |
| [setInstanceId(UUID guid)](#setInstanceId-java.util.UUID-) | インスタンス ID を設定します。 |
| [setInstanceId_internalized(System.Guid guid)](#setInstanceId-internalized-com.aspose.ms.System.Guid-) |  |
| [setOriginalDocumentId(String guid)](#setOriginalDocumentId-java.lang.String-) | 元のドキュメント ID を設定します。 |
| [setOriginalDocumentId(UUID guid)](#setOriginalDocumentId-java.util.UUID-) | 元のドキュメント ID を設定します。 |
| [setOriginalDocumentId_internalized(System.Guid guid)](#setOriginalDocumentId-internalized-com.aspose.ms.System.Guid-) |  |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | 値を設定します。 |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | XMP のブール値を設定します。 |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | XMP の一意識別子を設定します。 |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | XMP のタイプ値を設定します。 |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 指定されたキーで  オブジェクト  を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMediaManagementPackage() {#XmpMediaManagementPackage--}
```
public XmpMediaManagementPackage()
```


XmpMediaManagementPackage クラスの新しいインスタンスを初期化します。

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
### setDerivedFrom(ResourceRef resourceRef) {#setDerivedFrom-com.aspose.psd.xmp.types.complex.resourceref.ResourceRef-}
```
public void setDerivedFrom(ResourceRef resourceRef)
```


派生元を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| resourceRef | [ResourceRef](../../com.aspose.psd.xmp.types.complex.resourceref/resourceref) | リソース参照です。 |

### setDocumentId(String guid) {#setDocumentId-java.lang.String-}
```
public void setDocumentId(String guid)
```


ドキュメント識別子を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| guid | java.lang.String | 一意の識別子です。 |

### setDocumentId(UUID guid) {#setDocumentId-java.util.UUID-}
```
public void setDocumentId(UUID guid)
```


ドキュメント識別子を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| guid | java.util.UUID | 一意の識別子です。 |

### setDocumentId_internalized(System.Guid guid) {#setDocumentId-internalized-com.aspose.ms.System.Guid-}
```
public void setDocumentId_internalized(System.Guid guid)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| guid | com.aspose.ms.System.Guid |  |

### setInstanceId(String guid) {#setInstanceId-java.lang.String-}
```
public void setInstanceId(String guid)
```


インスタンス ID を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| guid | java.lang.String | 一意の識別子です。 |

### setInstanceId(UUID guid) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID guid)
```


インスタンス ID を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| guid | java.util.UUID | 一意の識別子です。 |

### setInstanceId_internalized(System.Guid guid) {#setInstanceId-internalized-com.aspose.ms.System.Guid-}
```
public void setInstanceId_internalized(System.Guid guid)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| guid | com.aspose.ms.System.Guid |  |

### setOriginalDocumentId(String guid) {#setOriginalDocumentId-java.lang.String-}
```
public void setOriginalDocumentId(String guid)
```


元のドキュメント ID を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| guid | java.lang.String | 一意の識別子です。 |

### setOriginalDocumentId(UUID guid) {#setOriginalDocumentId-java.util.UUID-}
```
public void setOriginalDocumentId(UUID guid)
```


元のドキュメント ID を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| guid | java.util.UUID | 一意の識別子です。 |

### setOriginalDocumentId_internalized(System.Guid guid) {#setOriginalDocumentId-internalized-com.aspose.ms.System.Guid-}
```
public void setOriginalDocumentId_internalized(System.Guid guid)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| guid | com.aspose.ms.System.Guid |  |

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

