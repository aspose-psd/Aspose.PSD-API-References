---
title: "LinkResource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "PSD 形式画像内のリンクまたは埋め込みファイルに関する情報を含む LinkResource クラスを定義します。"
type: docs
weight: 14
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public abstract class LinkResource extends LayerResource
```

LinkResource クラスを定義します。このクラスは PSD 形式画像におけるリンクまたは埋め込みファイルに関する情報を含みます。リンクリソースは、派生クラスのインデクサーでアクセス可能な複数の [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) インスタンスを含む場合があります。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [CannotAddTheDataSourceMessage_internalized](#CannotAddTheDataSourceMessage-internalized) | 「データ ソースを追加できません」メッセージ |
| [DataSourceTypeIsWrongMessage_internalized](#DataSourceTypeIsWrongMessage-internalized) | 「データ ソースのタイプが間違っています」メッセージ |
| [LengthOSourceLengthField](#LengthOSourceLengthField) | データ ソース長フィールドの長さ。 |
| [LengthOfResourceLengthField](#LengthOfResourceLengthField) | 総リソース長フィールドの長さ。 |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB ヘッダー バージョン |
| [PsbResourceSignature](#PsbResourceSignature) | PSB 固有のリソース署名。 |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD ヘッダー バージョン |
| [ResourceSignature](#ResourceSignature) | 共通リソース署名。 |
| [ventureLicense_internalized](#ventureLicense-internalized) | ベンチャー ライセンス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addDataSource_internalized(LinkDataSource dataSource)](#addDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | データ ソースを追加します。 |
| [addOrReplaceDataSource_internalized(LinkDataSource dataSource)](#addOrReplaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | データ ソースを追加または置換します。 |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | リソースが PSB 固有かどうかをチェックし、設定します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSourceCount()](#getDataSourceCount--) | インデクサでアクセス可能なリンク データ ソースの数を取得します。 |
| [getDataSources_internalized()](#getDataSources-internalized--) | データ ソースの LinkDataSource[] 配列を取得します。 |
| [getHeader_internalized()](#getHeader-internalized--) | ヘッダーを取得または設定します。 |
| [getKey()](#getKey--) | レイヤーリソースキーを取得します。 |
| [getLength()](#getLength--) | PSD グローバルリンクリソースの長さ（バイト単位）を取得します。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | プレフィックスの長さを取得します。 |
| [getPsdVersion()](#getPsdVersion--) | レイヤーリソースに必要な最小の psd バージョンを取得します。 |
| [getSignature()](#getSignature--) | レイヤーリソースのシグネチャを取得します。 |
| [getType_internalized()](#getType-internalized--) | PSD グローバルリンクリソースのタイプを取得または設定します。このタイプは以下のいずれか、またはなしにできます：Lnk2Resource および Lnk3Resource に対応する埋め込みリンクファイル liFD、LnkeResource に対応する外部リンクファイル liFE、リンクファイルエイリアス liFA |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスの [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) を取得します。 |
| [get_Item(UUID index)](#get-Item-java.util.UUID-) | 指定されたインデックスの [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) を取得します。これはリンク データ ソースの一意識別子です。 |
| [get_Item_internalized(System.Guid index)](#get-Item-internalized-com.aspose.ms.System.Guid-) |  |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) | このリンクリソースインスタンスが空かどうかを示す値を取得します。 |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | リソースが PSB 固有かどうかを判定します。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | このインスタンスがリソース PSB 固有かどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeDataSource_internalized(System.Guid uniqueId)](#removeDataSource-internalized-com.aspose.ms.System.Guid-) | リンクデータソースを削除します。 |
| [replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | データソースを置き換えます。 |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | リソースブロックデータを保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | カスタムリソースヘッダーを保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | ヘッダーのシグネチャ、識別子、長さを保存します。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | ヘッダーを取得または設定します。 |
| [toString()](#toString--) | このインスタンスを表す String を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CannotAddTheDataSourceMessage_internalized {#CannotAddTheDataSourceMessage-internalized}
```
public static final String CannotAddTheDataSourceMessage_internalized
```


「データ ソースを追加できません」メッセージ

### DataSourceTypeIsWrongMessage_internalized {#DataSourceTypeIsWrongMessage-internalized}
```
public static final String DataSourceTypeIsWrongMessage_internalized
```


「データ ソースのタイプが間違っています」メッセージ

### LengthOSourceLengthField {#LengthOSourceLengthField}
```
public static final int LengthOSourceLengthField
```


データ ソース長フィールドの長さ。

### LengthOfResourceLengthField {#LengthOfResourceLengthField}
```
public static final int LengthOfResourceLengthField
```


総リソース長フィールドの長さ。

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB ヘッダー バージョン

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


PSB 固有のリソース署名。

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD ヘッダー バージョン

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


共通リソース署名。

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


ベンチャー ライセンス。

### addDataSource_internalized(LinkDataSource dataSource) {#addDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void addDataSource_internalized(LinkDataSource dataSource)
```


データ ソースを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | リンク データ ソースです。 |

### addOrReplaceDataSource_internalized(LinkDataSource dataSource) {#addOrReplaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void addOrReplaceDataSource_internalized(LinkDataSource dataSource)
```


データ ソースを追加または置換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | データソース。 |

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


リソースが PSB 固有かどうかをチェックし、設定します。現在、一部のリソースは認識されていませんが、保存時の動作を変更する PSB 固有リソースの完全なリストがあります。そのため、少なくとも UnknownResource でこれをチェックする必要があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | int | キーです。 |

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
### getDataSourceCount() {#getDataSourceCount--}
```
public final int getDataSourceCount()
```


インデクサでアクセス可能なリンク データ ソースの数を取得します。

値: データソースの数。

**Returns:**
int
### getDataSources_internalized() {#getDataSources-internalized--}
```
public final LinkDataSource[] getDataSources_internalized()
```


データ ソースの LinkDataSource[] 配列を取得します。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


ヘッダーを取得または設定します。

値: ヘッダー。

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


レイヤーリソースキーを取得します。

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


PSD グローバルリンクリソースの長さ（バイト単位）を取得します。

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


プレフィックスの長さを取得します。8BIM リソースの場合はデフォルト値が 12、8B64 の場合は 16 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| psdVersion | int | PSD バージョン。 |

**Returns:**
int - プレフィックスの長さ。
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


レイヤーリソースに必要な最小の psd バージョンを取得します。0 は制限がないことを示します。

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


レイヤーリソースのシグネチャを取得します。

**Returns:**
int
### getType_internalized() {#getType-internalized--}
```
public final int getType_internalized()
```


PSD グローバルリンクリソースのタイプを取得または設定します。このタイプは以下のいずれか、またはなしにできます：Lnk2Resource および Lnk3Resource に対応する埋め込みリンクファイル liFD、LnkeResource に対応する外部リンクファイル liFE、リンクファイルエイリアス liFA

値: PSDリンクリソースのタイプ。

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public LinkDataSource get_Item(int index)
```


指定されたインデックスの [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 整数インデックス。値: [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)。 |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### get_Item(UUID index) {#get-Item-java.util.UUID-}
```
public final LinkDataSource get_Item(UUID index)
```


指定されたインデックスの [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) を取得します。これはリンク データ ソースの一意識別子です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | java.util.UUID | インデックスはリンクデータソースの一意識別子です。値: [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)。 |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### get_Item_internalized(System.Guid index) {#get-Item-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource get_Item_internalized(System.Guid index)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | com.aspose.ms.System.Guid |  |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


このリンクリソースインスタンスが空かどうかを示す値を取得します。

値: このリンクリソースが空の場合は true、そうでない場合は false。

**Returns:**
boolean
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


リソースが PSB 固有かどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | int | リソースキーです。 |

**Returns:**
boolean - リソースが PSB 固有の場合は true、そうでない場合は false。
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


このインスタンスがリソース PSB 固有かどうかを示す値を取得します。

値: このインスタンスがリソース PSB 固有の場合は true、そうでない場合は false。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeDataSource_internalized(System.Guid uniqueId) {#removeDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final void removeDataSource_internalized(System.Guid uniqueId)
```


リンクデータソースを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | 一意の識別子です。 |

### replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void replaceDataSource_internalized(System.Guid uniqueId, LinkDataSource dataSource)
```


データソースを置き換えます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | 一意の識別子です。 |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | リンク データ ソースです。 |

### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


リソースブロックデータを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |
| psdVersion | int | PSD バージョン。 |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


カスタムリソースヘッダーを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |
| 署名 | int | シグネチャです。 |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


ヘッダーのシグネチャ、識別子、長さを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |
| 署名 | int | シグネチャです。 |
| isLengthLong | boolean | true に設定すると、長さは長くなります。 |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


ヘッダーを取得または設定します。

値: ヘッダー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### toString() {#toString--}
```
public String toString()
```


このインスタンスを表す String を返します。

**Returns:**
java.lang.String - このインスタンスを表す文字列です。
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

