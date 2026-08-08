---
title: "XmpBasicPackage"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "XMP 基本名前空間を表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

XMP 基本名前空間を表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | XmpBasicPackage クラスの新しいインスタンスを初期化します。 |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | XmpBasicPackage クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [RatingMax](#RatingMax) | 評価の最大値。 |
| [RatingMin](#RatingMin) | 評価の最小値。 |
| [RatingRejected](#RatingRejected) | 評価の拒否値。 |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | 指定されたキーでオブジェクトを取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | 指定されたキーの値を削除します。 |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | リソース作成日を追加します。 |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | リソース作成日を追加します。 |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | 作成ツールを設定します。 |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | 識別子を設定します。 |
| [setLabel(String label)](#setLabel-java.lang.String-) | ラベルを設定します。 |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | メタデータの最終変更日を追加します。 |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | メタデータの最終変更日を追加します。 |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | リソースの最終更新日を追加します。 |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | リソースの最終更新日を追加します。 |
| [setRating(int choise)](#setRating-int-) | 評価を設定します。 |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | 値を設定します。 |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | XMP のブール値を設定します。 |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | XMP の一意識別子を設定します。 |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | XMP のタイプ値を設定します。 |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 指定されたキーでオブジェクトを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


XmpBasicPackage クラスの新しいインスタンスを初期化します。

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


XmpBasicPackage クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| プレフィックス | java.lang.String | プレフィックスです。 |
| namespaceUri | java.lang.String | 名前空間 URIです。 |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


評価の最大値。

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


評価の最小値。

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


評価の拒否値。

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


指定されたキーでオブジェクトを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | 値を識別するキーです。値: Object。 |

**Returns:**
java.lang.Object - 指定されたキーを持つ Object を返します。
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
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


リソース作成日を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createdDate | java.lang.String | 作成日。 |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


リソース作成日を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | 作成日。 |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


作成ツールを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| creatorTool | java.lang.String | ツールの名前。 |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


識別子を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| idenfifier | java.lang.String[] | idenfifierです。 |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


ラベルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| label | java.lang.String | ラベルです。 |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


メタデータの最終変更日を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| metadataDate | java.lang.String | メタデータの日付。 |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


メタデータの最終変更日を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | メタデータの日付。 |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


リソースの最終更新日を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| modifiedDate | java.lang.String | 最終更新日。 |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


リソースの最終更新日を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | 最終更新日。 |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


評価を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| choise | int | -1 から 5 まで |

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


指定されたキーでオブジェクトを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | 値を識別するキーです。値: Object。 |
| 値 | java.lang.Object |  |

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

