---
title: "SmartObjectProvider"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mendefinisikan penyedia objek pintar yang menyediakan pengambilan / penetapan sumber data dari sumber tautan global file PSD dan isinya."
type: docs
weight: 17
url: /id/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

Mendefinisikan penyedia objek pintar yang menyediakan pengambilan / penetapan sumber data dari sumber tautan global file PSD dan isinya.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | Mengonversi lapisan menjadi objek pintar tersemat. |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | Mengonversi lapisan menjadi objek pintar tersemat. |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | Menginisialisasi instance baru dari kelas [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider). |
| [embedAllLinked()](#embedAllLinked--) | Menyematkan semua objek pintar tertaut dalam gambar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | Mendapatkan tipe konten lapisan objek pintar. |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | Mendapatkan isi file yang tersemat atau tertaut. |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | Mendapatkan sumber data tautan berdasarkan id unik. |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | Memuat isi. |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | Membuat lapisan objek pintar baru dengan menyalin lapisan sumber. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | Menghapus sumber data dari sumber daya tersemat dan eksternal yang tidak ada dalam daftar GUID valid yang diberikan. |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | Mengganti sumber data dalam sumber daya global dengan konten yang disediakan untuk disematkan. |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | Mengganti sumber data dalam sumber daya global LinkResource dengan sumber data baru yang dibuat dari file eksternal. |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | Mengatur isi file yang tersemat atau eksternal. |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Mengatur (mengganti atau menambah) sumber data tautan dalam sumber daya tautan global. |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | Memperbarui konten semua objek pintar yang dimodifikasi dalam gambar. |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | Memperbarui semua lapisan objek pintar dalam kontainer yang  UniqueId  cocok dengan  oldGuid . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


Mengonversi lapisan menjadi objek pintar tersemat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Lapisan. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


Mengonversi lapisan menjadi objek pintar tersemat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layerNumbers | int[] | Nomor lapisan. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


Menginisialisasi instance baru dari kelas [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Kontainer. |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


Menyematkan semua objek pintar tertaut dalam gambar.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mendapatkan tipe konten lapisan objek pintar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Pengidentifikasi unik. |

**Returns:**
int - Tipe konten lapisan objek pintar.
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


Mendapatkan isi file yang tersemat atau tertaut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Pengidentifikasi unik dari sumber data tautan. |

**Returns:**
byte[] - Konten byte[] .
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


Mendapatkan sumber data tautan berdasarkan id unik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Pengidentifikasi unik. |

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


Memuat isi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Pengidentifikasi unik. |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | Opsi pemuatan. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


Membuat lapisan objek pintar baru dengan menyalin lapisan sumber.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | Lapisan sumber. |

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


Menghapus sumber data dari sumber daya yang disematkan dan eksternal yang tidak ada dalam daftar GUID yang valid yang diberikan. Metode ini membersihkan sumber data yang tidak terpakai dengan membandingkannya dengan pengidentifikasi sumber data yang valid saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | Daftar GUID sumber data yang valid untuk dipertahankan. Sumber data yang tidak ada dalam daftar ini akan dihapus. |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


Mengganti sumber data dalam sumber daya global dengan konten yang disediakan untuk disematkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | Pengidentifikasi unik dari sumber data yang ada. |
| contents | byte[] | Data untuk sumber data baru. |

**Returns:**
com.aspose.ms.System.Guid - Pengidentifikasi unik dari sumber data tersemat yang dibuat.  LiFdDataSource .
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


Mengganti sumber data dalam sumber daya global LinkResource dengan sumber data baru yang dibuat dari file eksternal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Sumber daya yang ditempatkan. |
| linkedPath | java.lang.String | Path absolut ke file yang ditautkan. |
| isReplaceOnlyThis | boolean | Jika true, maka jangan hapus sumber data di sumber daya global. |

**Returns:**
com.aspose.ms.System.Guid - Guid pengidentifikasi unik dari sumber data tertaut yang dibuat. [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


Mengatur isi file yang tersemat atau eksternal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Pengidentifikasi unik dari sumber data tautan. |
| data | byte[] | Data. |
| fileType | java.lang.String | Tipe file data. |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


Mengatur (mengganti atau menambah) sumber data tautan dalam sumber daya tautan global.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Sumber data tautan. |

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


Memperbarui konten semua objek pintar yang dimodifikasi dalam gambar.

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


Memperbarui semua lapisan objek pintar dalam wadah yang UniqueId cocok dengan oldGuid. UniqueId lapisan yang cocok dipindahkan ke newGuid dan kontennya disegarkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | Pengidentifikasi unik dari sumber data objek pintar asli yang akan diganti. |
| newGuid | com.aspose.ms.System.Guid | Pengidentifikasi unik dari sumber data objek pintar baru yang akan ditetapkan. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Pengaturan resolusi yang diterapkan saat memperbarui konten. Jika null, resolusi gambar yang digunakan. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

