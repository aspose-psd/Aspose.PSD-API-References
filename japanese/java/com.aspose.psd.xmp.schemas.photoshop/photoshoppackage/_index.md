---
title: "PhotoshopPackage"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "Adobe Photoshop の名前空間を表します。"
type: docs
weight: 12
url: /ja/java/com.aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class PhotoshopPackage extends XmpPackage
```

Adobe Photoshop の名前空間を表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PhotoshopPackage()](#PhotoshopPackage--) | PhotoshopPackage クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [UrgencyMax](#UrgencyMax) | 緊急度の最大値。 |
| [UrgencyMin](#UrgencyMin) | 緊急度の最小値。 |
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
| [setAuthorsPosition(String authorsPosition)](#setAuthorsPosition-java.lang.String-) | 作者の位置を設定します。 |
| [setCaptionWriter(String captionWriter)](#setCaptionWriter-java.lang.String-) | キャプション作成者を設定します。 |
| [setCategory(String category)](#setCategory-java.lang.String-) | カテゴリを設定します。 |
| [setCity(String city)](#setCity-java.lang.String-) | 都市を設定します。 |
| [setColorMode(byte colorMode)](#setColorMode-byte-) | カラーモードを設定します。 |
| [setCountry(String country)](#setCountry-java.lang.String-) | 国を設定します。 |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | 作成日を設定します。 |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setCredit(String credit)](#setCredit-java.lang.String-) | クレジットを設定します。 |
| [setDocumentAncestors(String[] ancestors)](#setDocumentAncestors-java.lang.String---) | ドキュメントの祖先を設定します。 |
| [setHeadline(String headline)](#setHeadline-java.lang.String-) | 見出しを設定します。 |
| [setHistory(String history)](#setHistory-java.lang.String-) | 履歴を設定します。 |
| [setIccProfile(String iccProfile)](#setIccProfile-java.lang.String-) | ICC プロファイルを設定します。 |
| [setInstructions(String instructions)](#setInstructions-java.lang.String-) | 指示を設定します。 |
| [setSource(String source)](#setSource-java.lang.String-) | ソースを設定します。 |
| [setState(String state)](#setState-java.lang.String-) | 状態を設定します。 |
| [setSupplementalCategories(String[] supplementalCategories)](#setSupplementalCategories-java.lang.String---) | 補足カテゴリを設定します。 |
| [setTransmissionReference(String transmissionReference)](#setTransmissionReference-java.lang.String-) | 送信参照を設定します。 |
| [setUrgency(int urgency)](#setUrgency-int-) | 緊急度を設定します。 |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | 値を設定します。 |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | XMP のブール値を設定します。 |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | XMP の一意識別子を設定します。 |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | XMP のタイプ値を設定します。 |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | 指定されたキーで  オブジェクト  を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhotoshopPackage() {#PhotoshopPackage--}
```
public PhotoshopPackage()
```


PhotoshopPackage クラスの新しいインスタンスを初期化します。

### UrgencyMax {#UrgencyMax}
```
public static final int UrgencyMax
```


緊急度の最大値。

### UrgencyMin {#UrgencyMin}
```
public static final int UrgencyMin
```


緊急度の最小値。

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
### setAuthorsPosition(String authorsPosition) {#setAuthorsPosition-java.lang.String-}
```
public void setAuthorsPosition(String authorsPosition)
```


作者の位置を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| authorsPosition | java.lang.String | 著者の位置。 |

### setCaptionWriter(String captionWriter) {#setCaptionWriter-java.lang.String-}
```
public void setCaptionWriter(String captionWriter)
```


キャプション作成者を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| captionWriter | java.lang.String | キャプションライター。 |

### setCategory(String category) {#setCategory-java.lang.String-}
```
public void setCategory(String category)
```


カテゴリを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| category | java.lang.String | カテゴリ。 |

### setCity(String city) {#setCity-java.lang.String-}
```
public void setCity(String city)
```


都市を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| city | java.lang.String | 都市名。 |

### setColorMode(byte colorMode) {#setColorMode-byte-}
```
public void setColorMode(byte colorMode)
```


カラーモードを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorMode | byte | カラーモード。 |

### setCountry(String country) {#setCountry-java.lang.String-}
```
public void setCountry(String country)
```


国を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| country | java.lang.String | 国。 |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


作成日を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createdDate | java.util.Date | 作成日。 |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime |  |

### setCredit(String credit) {#setCredit-java.lang.String-}
```
public void setCredit(String credit)
```


クレジットを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| クレジット | java.lang.String | クレジットです。 |

### setDocumentAncestors(String[] ancestors) {#setDocumentAncestors-java.lang.String---}
```
public void setDocumentAncestors(String[] ancestors)
```


ドキュメントの祖先を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 先祖 | java.lang.String[] | 先祖です。 |

### setHeadline(String headline) {#setHeadline-java.lang.String-}
```
public void setHeadline(String headline)
```


見出しを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 見出し | java.lang.String | 見出しです。 |

### setHistory(String history) {#setHistory-java.lang.String-}
```
public void setHistory(String history)
```


履歴を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 履歴 | java.lang.String | 履歴です。 |

### setIccProfile(String iccProfile) {#setIccProfile-java.lang.String-}
```
public void setIccProfile(String iccProfile)
```


ICC プロファイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| iccProfile | java.lang.String | icc プロファイルです。 |

### setInstructions(String instructions) {#setInstructions-java.lang.String-}
```
public void setInstructions(String instructions)
```


指示を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 指示 | java.lang.String | 指示です。 |

### setSource(String source) {#setSource-java.lang.String-}
```
public void setSource(String source)
```


ソースを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ソース | java.lang.String | ソースです。 |

### setState(String state) {#setState-java.lang.String-}
```
public void setState(String state)
```


状態を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 状態 | java.lang.String | 状態です。 |

### setSupplementalCategories(String[] supplementalCategories) {#setSupplementalCategories-java.lang.String---}
```
public void setSupplementalCategories(String[] supplementalCategories)
```


補足カテゴリを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| supplementalCategories | java.lang.String[] | 補足カテゴリです。 |

### setTransmissionReference(String transmissionReference) {#setTransmissionReference-java.lang.String-}
```
public void setTransmissionReference(String transmissionReference)
```


送信参照を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| transmissionReference | java.lang.String | 送信参照です。 |

### setUrgency(int urgency) {#setUrgency-int-}
```
public void setUrgency(int urgency)
```


緊急度を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 緊急度 | int | 緊急度です。 |

緊急度は 1 から 8 の範囲である必要があります。 |

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

