---
title: "SmartObjectProvider"
second_title: "Java için Aspose.PSD API Referansı"
description: "PSD dosyasının global bağlantı kaynaklarından veri kaynaklarını alma / ayarlama ve içeriklerini sağlayan akıllı nesne sağlayıcısını tanımlar."
type: docs
weight: 17
url: /tr/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

PSD dosyasının global bağlantı kaynaklarından veri kaynaklarını alma / ayarlama ve içeriklerini sağlayan akıllı nesne sağlayıcısını tanımlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | Katmanları gömülü bir akıllı nesneye dönüştürür. |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | Katmanları gömülü bir akıllı nesneye dönüştürür. |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | Yeni bir [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider) sınıfı örneği başlatır. |
| [embedAllLinked()](#embedAllLinked--) | Görüntüdeki tüm bağlı akıllı nesneleri gömer. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | Akıllı nesne katman içeriğinin türünü alır. |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | Gömülü veya bağlı dosya içeriklerini alır. |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | Benzersiz kimliğe göre bağlantı veri kaynağını alır. |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | İçerikleri yükler. |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | Kaynak katmanı kopyalayarak yeni bir akıllı nesne katmanı oluşturur. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | Sağlanan geçerli GUID listesinde bulunmayan gömülü ve harici kaynaklardan veri kaynaklarını kaldırır. |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | Gömmek için sağlanan içeriklerle küresel kaynaklardaki veri kaynağını değiştirir. |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | Harici dosyadan yeni oluşturulan veri kaynağıyla küresel LinkResource kaynaklarındaki veri kaynağını değiştirir. |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | Gömülü veya harici dosya içeriklerini ayarlar. |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Küresel bağlantı kaynağında bağlantı veri kaynağını ayarlar (değiştirir veya ekler). |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | Görüntüdeki tüm değiştirilmiş akıllı nesnelerin içeriğini günceller. |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | Konteyner içinde UniqueId'si oldGuid ile eşleşen tüm akıllı nesne katmanlarını günceller. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


Katmanları gömülü bir akıllı nesneye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Katmanlar. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


Katmanları gömülü bir akıllı nesneye dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layerNumbers | int[] | Katman numaraları. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


Yeni bir [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Konteyner. |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


Görüntüdeki tüm bağlı akıllı nesneleri gömer.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Akıllı nesne katman içeriğinin türünü alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Benzersiz tanımlayıcı. |

**Returns:**
int - Akıllı nesne katman içeriğinin türü.
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


Gömülü veya bağlı dosya içeriklerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Bağlantı veri kaynağının benzersiz tanımlayıcısı. |

**Returns:**
byte[] - byte[] içeriği.
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


Benzersiz kimliğe göre bağlantı veri kaynağını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Benzersiz tanımlayıcı. |

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


İçerikleri yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Benzersiz tanımlayıcı. |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


Kaynak katmanı kopyalayarak yeni bir akıllı nesne katmanı oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | Kaynak katman. |

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


Sağlanan geçerli GUID listesinde bulunmayan gömülü ve harici kaynaklardan veri kaynaklarını kaldırır. Bu yöntem, mevcut geçerli veri kaynağı tanımlayıcılarıyla karşılaştırarak yetim veri kaynaklarını temizler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | Tutulacak geçerli veri kaynağı GUID'lerinin listesi. Bu listedeki olmayan veri kaynakları kaldırılacaktır. |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


Gömmek için sağlanan içeriklerle küresel kaynaklardaki veri kaynağını değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | Mevcut veri kaynağının benzersiz tanımlayıcısı. |
| contents | byte[] | Yeni bir veri kaynağı için veri. |

**Returns:**
com.aspose.ms.System.Guid - Oluşturulan gömülü veri kaynağının benzersiz tanımlayıcısı.  LiFdDataSource .
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


Harici dosyadan yeni oluşturulan veri kaynağıyla küresel LinkResource kaynaklarındaki veri kaynağını değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Yerleştirilen kaynak. |
| linkedPath | java.lang.String | Bağlı dosyanın mutlak yolu. |
| isReplaceOnlyThis | boolean | Doğruysa, küresel kaynaklardaki veri kaynağını kaldırma. |

**Returns:**
com.aspose.ms.System.Guid - Oluşturulan bağlı veri kaynağının benzersiz tanımlayıcı GUID'si. [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


Gömülü veya harici dosya içeriklerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Bağlantı veri kaynağının benzersiz tanımlayıcısı. |
| veri | byte[] | Veri. |
| fileType | java.lang.String | Veri dosyası türü. |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


Küresel bağlantı kaynağında bağlantı veri kaynağını ayarlar (değiştirir veya ekler).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Bağlantı veri kaynağı. |

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


Görüntüdeki tüm değiştirilmiş akıllı nesnelerin içeriğini günceller.

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


Kapsayıcı içindeki  UniqueId  si oldGuid ile eşleşen tüm akıllı nesne katmanlarını günceller. Eşleşen katmanların  UniqueId  si newGuid olarak yeniden atanır ve içerikleri yenilenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | Değiştirilecek orijinal akıllı nesne veri kaynağının benzersiz tanımlayıcısı. |
| newGuid | com.aspose.ms.System.Guid | Atanacak yeni akıllı nesne veri kaynağının benzersiz tanımlayıcısı. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | İçeriği güncellerken uygulanacak çözünürlük ayarları. Eğer null ise, görüntü çözünürlüğü kullanılır. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

