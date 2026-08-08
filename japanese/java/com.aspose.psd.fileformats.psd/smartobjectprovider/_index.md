---
title: "SmartObjectProvider"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "PSD ファイルのグローバルリンクリソースおよびその内容からデータソースを取得/設定するスマートオブジェクトプロバイダーを定義します。"
type: docs
weight: 17
url: /ja/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

PSD ファイルのグローバルリンクリソースおよびその内容からデータソースを取得/設定するスマートオブジェクトプロバイダーを定義します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | レイヤーを埋め込みスマートオブジェクトに変換します。 |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | レイヤーを埋め込みスマートオブジェクトに変換します。 |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | 新しい [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider) クラスのインスタンスを初期化します。 |
| [embedAllLinked()](#embedAllLinked--) | 画像内のすべてのリンクされたスマートオブジェクトを埋め込みます。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | スマートオブジェクトレイヤーコンテンツのタイプを取得します。 |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | 埋め込みまたはリンクされたファイルの内容を取得します。 |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | 一意の ID によるリンクデータソースを取得します。 |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | 内容をロードします。 |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | ソースレイヤーをコピーして新しいスマートオブジェクトレイヤーを作成します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | 提供された有効な GUID のリストに存在しない、埋め込みおよび外部リソースからデータソースを削除します。 |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | グローバルリソース内のデータソースを、埋め込むために提供された内容に置き換えます。 |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | グローバル LinkResource のデータソースを、外部ファイルから作成された新しいデータソースに置き換えます。 |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | 埋め込みまたは外部ファイルの内容を設定します。 |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | グローバルリンクリソース内のリンクデータソースを設定（置換または追加）します。 |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | 画像内のすべての変更されたスマートオブジェクトのコンテンツを更新します。 |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | コンテナ内で UniqueId が oldGuid と一致するすべてのスマートオブジェクトレイヤーを更新します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


レイヤーを埋め込みスマートオブジェクトに変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | レイヤー。 |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


レイヤーを埋め込みスマートオブジェクトに変換します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| layerNumbers | int[] | レイヤー番号です。 |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


新しい [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | コンテナです。 |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


画像内のすべてのリンクされたスマートオブジェクトを埋め込みます。

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
### getContentType_internalized(System.Guid uniqueId) {#getContentType-internalized-com.aspose.ms.System.Guid-}
```
public final int getContentType_internalized(System.Guid uniqueId)
```


スマートオブジェクトレイヤーコンテンツのタイプを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | 一意の識別子です。 |

**Returns:**
int - スマートオブジェクトレイヤーコンテンツのタイプです。
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


埋め込みまたはリンクされたファイルの内容を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | リンクデータソースの一意識別子です。 |

**Returns:**
byte[] - byte[] の内容です。
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


一意の ID によるリンクデータソースを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | 一意の識別子です。 |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadContents_internalized(System.Guid uniqueId, LoadOptions options) {#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-}
```
public final Image loadContents_internalized(System.Guid uniqueId, LoadOptions options)
```


内容をロードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | 一意の識別子です。 |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | ロードオプションです。 |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


ソースレイヤーをコピーして新しいスマートオブジェクトレイヤーを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | ソースレイヤーです。 |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The cloned [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources) {#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--}
```
public final void removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)
```


提供された有効な GUID のリストに存在しない埋め込みおよび外部リソースからデータソースを削除します。このメソッドは、現在の有効なデータソース識別子と比較することで、孤立したデータソースをクリーンアップします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | 保持する有効なデータソース GUID のリストです。このリストに含まれないデータソースは削除されます。 |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


グローバルリソース内のデータソースを、埋め込むために提供された内容に置き換えます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | 既存のデータソースの一意識別子です。 |
| contents | byte[] | 新しいデータソースのデータです。 |

**Returns:**
com.aspose.ms.System.Guid - 作成された埋め込みデータソースの一意識別子です。  LiFdDataSource .
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


グローバル LinkResource のデータソースを、外部ファイルから作成された新しいデータソースに置き換えます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | 配置されたリソースです。 |
| linkedPath | java.lang.String | リンクされたファイルへの絶対パスです。 |
| isReplaceOnlyThis | boolean | true の場合、グローバルリソース内のデータソースは削除しません。 |

**Returns:**
com.aspose.ms.System.Guid - 作成されたリンクデータソースの一意識別子 Guid です。 [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


埋め込みまたは外部ファイルの内容を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | リンクデータソースの一意識別子です。 |
| データ | byte[] | データ。 |
| fileType | java.lang.String | データファイルの種類です。 |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


グローバルリンクリソース内のリンクデータソースを設定（置換または追加）します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | リンク データ ソースです。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateAllModifiedContent() {#updateAllModifiedContent--}
```
public final void updateAllModifiedContent()
```


画像内のすべての変更されたスマートオブジェクトのコンテンツを更新します。

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


コンテナ内のすべてのスマートオブジェクトレイヤーで、UniqueId が oldGuid と一致するものを更新します。該当するレイヤーの UniqueId は newGuid に再割り当てされ、コンテンツが更新されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | 置き換えられる元のスマートオブジェクトデータソースの一意識別子です。 |
| newGuid | com.aspose.ms.System.Guid | 割り当てる新しいスマートオブジェクトデータソースの一意識別子です。 |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | コンテンツを更新する際に適用する解像度設定です。null の場合、画像の解像度が使用されます。 |

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

