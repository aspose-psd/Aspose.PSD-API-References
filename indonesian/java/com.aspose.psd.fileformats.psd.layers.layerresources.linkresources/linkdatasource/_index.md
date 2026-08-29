---
title: "LinkDataSource"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mendefinisikan kelas LinkDataSource yang berisi informasi tentang file yang ditautkan atau aset dalam file PSD."
type: docs
weight: 12
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource/
---

**Inheritance:**
java.lang.Object
```
public abstract class LinkDataSource
```

Mendefinisikan kelas LinkDataSource yang berisi informasi tentang file yang ditautkan atau aset dalam file PSD.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | Versi deskriptor. |
| [LatestVersion_internalized](#LatestVersion-internalized) | Versi terbaru yang tersedia dari sumber data tautan |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | Nilai tipe sumber data tautan yang tidak terduga |
| [ZeroChar_internalized](#ZeroChar-internalized) | Karakter nol |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssetLockedState()](#getAssetLockedState--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah aset PSD terkunci. |
| [getAssetModTime()](#getAssetModTime--) | Mendapatkan atau mengatur waktu modifikasi aset, untuk aset Adobe® Photoshop® \\u0421\\u0421 Libraries. |
| [getChildDocId()](#getChildDocId--) | Mendapatkan atau mengatur pengidentifikasi dokumen anak dalam sumber data liFE atau liFD dari sumber daya Lnk2 / LnkE Adobe® Photoshop®. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Mendapatkan atau mengatur id kelas sumber daya. |
| [getClassName_internalized()](#getClassName-internalized--) | Mendapatkan atau mengatur nama kelas sumber daya. |
| [getCompId()](#getCompId--) | Mendapatkan atau mengatur ID komponen yang saat ini dipilih untuk dokumen anak, yang akan menjadi -1 jika tidak ada yang dipilih. |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | Mendapatkan atau mengatur properti ContentID. |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | Mendapatkan panjang data tambahan. |
| [getDataLength_internalized()](#getDataLength-internalized--) | Mendapatkan panjang data sumber tautan. |
| [getFileCreator()](#getFileCreator--) | Mendapatkan atau mengatur pembuat file dalam sumber daya format PSD LnkE / Lnk2. |
| [getFileType()](#getFileType--) | Mendapatkan atau mengatur tipe file tersemat atau eksternal yang dimiliki atau ditautkan oleh sumber daya Adobe® Photoshop® Lnk2 / LnkE. |
| [getItems_internalized()](#getItems-internalized--) | Mendapatkan atau mengatur array OSTypeStructure yang mendefinisikan properti sumber daya. |
| [getLength()](#getLength--) | Mendapatkan panjang sumber data tautan dalam byte. |
| [getOriginalCompId()](#getOriginalCompId--) | Mendapatkan ID asli dari Comp yang saat ini dipilih untuk dokumen anak, yang akan menjadi -1 jika tidak ada yang dipilih. |
| [getOriginalFileName()](#getOriginalFileName--) | Mendapatkan nama file asli dari sumber data dalam sumber daya tautan global Adobe® Photoshop®. |
| [getType()](#getType--) | Mendapatkan tipe sumber data tautan global Adobe® Photoshop® yang dapat berupa salah satu dari berikut ini atau tidak ada: File tautan tersemat liFD yang sesuai dengan PSD Lnk2Resource File tautan eksternal liFE yang sesuai dengan PSD LnkeResource Alias file tautan liFA |
| [getUniqueId()](#getUniqueId--) | Mendapatkan pengenal unik global dari sumber data dalam sumber daya tautan PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Mendapatkan atau mengatur data tidak dikenal yang berada sebelum properti Items OSTypeStructures. |
| [getVersion()](#getVersion--) | Mendapatkan versi sumber data dalam sumber daya PSD LnkE / Lnk2. |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah sumber data tautan ini memiliki deskriptor file terbuka: CompId dan OriginalCompId. |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | Mendapatkan nilai yang menunjukkan apakah sumber data tautan PSD ini menautkan ke item Perpustakaan Adobe® Photoshop® \u0421\u0421. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Menyimpan data blok sumber data tautan. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah aset PSD terkunci. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Mendapatkan atau mengatur waktu modifikasi aset, untuk aset Adobe® Photoshop® \\u0421\\u0421 Libraries. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Mendapatkan atau mengatur pengidentifikasi dokumen anak dalam sumber data liFE atau liFD dari sumber daya Lnk2 / LnkE Adobe® Photoshop®. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Mendapatkan atau mengatur id kelas sumber daya. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Mendapatkan atau mengatur nama kelas sumber daya. |
| [setCompId(int value)](#setCompId-int-) | Mendapatkan atau mengatur ID komponen yang saat ini dipilih untuk dokumen anak, yang akan menjadi -1 jika tidak ada yang dipilih. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | Mendapatkan atau mengatur properti ContentID. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | Mendapatkan atau mengatur pembuat file dalam sumber daya format PSD LnkE / Lnk2. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah sumber data tautan ini memiliki deskriptor file terbuka: CompId dan OriginalCompId. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Mendapatkan atau mengatur tipe file tersemat atau eksternal yang dimiliki atau ditautkan oleh sumber daya Adobe® Photoshop® Lnk2 / LnkE. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Mendapatkan atau mengatur array OSTypeStructure yang mendefinisikan properti sumber daya. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Mendapatkan nilai yang menunjukkan apakah sumber data tautan PSD ini menautkan ke item Perpustakaan Adobe® Photoshop® \u0421\u0421. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Mendapatkan ID asli dari Comp yang saat ini dipilih untuk dokumen anak, yang akan menjadi -1 jika tidak ada yang dipilih. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Mendapatkan nama file asli dari sumber data dalam sumber daya tautan global Adobe® Photoshop®. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Mengatur nilai properti berdasarkan struktur tipe. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | Mendapatkan pengenal unik global dari sumber data dalam sumber daya tautan PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Mendapatkan atau mengatur data tidak dikenal yang berada sebelum properti Items OSTypeStructures. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


Versi deskriptor.

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


Versi terbaru yang tersedia dari sumber data tautan

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


Nilai tipe sumber data tautan yang tidak terduga

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


Karakter nol

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
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah aset PSD terkunci. Status terkunci aset, untuk aset Adobe® Photoshop® \u0421\u0421 Libraries.

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Mendapatkan atau mengatur waktu modifikasi aset, untuk aset Adobe® Photoshop® \\u0421\\u0421 Libraries.

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Mendapatkan atau mengatur pengidentifikasi dokumen anak dalam sumber data liFE atau liFD dari sumber daya Lnk2 / LnkE Adobe® Photoshop®.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Mendapatkan atau mengatur id kelas sumber daya.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Mendapatkan atau mengatur nama kelas sumber daya.

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


Mendapatkan atau mengatur ID komposisi yang saat ini dipilih untuk dokumen anak, yang akan bernilai -1 jika tidak ada yang dipilih. Komposisi adalah susunan tata letak halaman yang dapat dibuat oleh desainer. Dengan menggunakan layer comps, Anda dapat membuat, mengelola, dan melihat beberapa versi tata letak dalam satu file Adobe® Photoshop®. Sebuah layer comp adalah snapshot dari keadaan panel Layers. Layer comps menyimpan tiga jenis opsi layer tetapi properti ini mendapatkan identifier pemilihan Layer Comp untuk Smart Objects.  Layer comps in Smart Objects

**Returns:**
int
### getCompInfoKeyName() {#getCompInfoKeyName--}
```
public static String getCompInfoKeyName()
```




**Returns:**
java.lang.String
### getContentID_internalized() {#getContentID-internalized--}
```
public final String getContentID_internalized()
```


Mendapatkan atau mengatur properti ContentID. Nilai properti ini dibaca dan disimpan hanya ketika Versi >= 8.

**Returns:**
java.lang.String
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


Mendapatkan panjang data tambahan.

Nilai: Panjang data.

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


Mendapatkan panjang data sumber tautan.

**Returns:**
long - Panjang data sumber.
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


Mendapatkan atau mengatur pembuat file dalam sumber daya format PSD LnkE / Lnk2.

**Returns:**
java.lang.String
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Mendapatkan atau mengatur tipe file tersemat atau eksternal yang dimiliki atau ditautkan oleh sumber daya Adobe® Photoshop® Lnk2 / LnkE.

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


Mendapatkan atau mengatur array OSTypeStructure yang mendefinisikan properti sumber daya.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


Mendapatkan panjang sumber data tautan dalam byte.

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


Mendapatkan ID asli dari Comp yang saat ini dipilih untuk dokumen anak, yang akan bernilai -1 jika tidak ada yang dipilih. Properti ini mendapatkan identifier pemilihan layer Comp asli untuk Smart Objects.  Layer comps in Smart Objects

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Mendapatkan nama file asli dari sumber data dalam sumber daya tautan global Adobe® Photoshop®.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Mendapatkan tipe sumber data tautan global Adobe® Photoshop® yang dapat berupa salah satu dari berikut ini atau tidak ada: File tautan tersemat liFD yang sesuai dengan PSD Lnk2Resource File tautan eksternal liFE yang sesuai dengan PSD LnkeResource Alias file tautan liFA

Nilai: Tipe sumber data tautan PSD.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


Mendapatkan pengenal unik global dari sumber data dalam sumber daya tautan PSD.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public final System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getUnknownBytes_internalized() {#getUnknownBytes-internalized--}
```
public final byte[] getUnknownBytes_internalized()
```


Mendapatkan atau mengatur data tidak dikenal yang berada sebelum properti Items OSTypeStructures.

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Mendapatkan versi sumber data dalam sumber daya PSD LnkE / Lnk2.

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah sumber data tautan ini memiliki deskriptor file terbuka: CompId dan OriginalCompId.

Nilai:  true  jika instance ini memiliki deskriptor file terbuka; selainnya,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLibraryLink() {#isLibraryLink--}
```
public final boolean isLibraryLink()
```


Mendapatkan nilai yang menunjukkan apakah sumber data tautan PSD ini menautkan ke item Perpustakaan Adobe® Photoshop® \u0421\u0421.

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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


Menyimpan data blok sumber data tautan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah aset PSD terkunci. Status terkunci aset, untuk aset Adobe® Photoshop® \u0421\u0421 Libraries.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Mendapatkan atau mengatur waktu modifikasi aset, untuk aset Adobe® Photoshop® \\u0421\\u0421 Libraries.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Mendapatkan atau mengatur pengidentifikasi dokumen anak dalam sumber data liFE atau liFD dari sumber daya Lnk2 / LnkE Adobe® Photoshop®.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Mendapatkan atau mengatur id kelas sumber daya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Mendapatkan atau mengatur nama kelas sumber daya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


Mendapatkan atau mengatur ID komposisi yang saat ini dipilih untuk dokumen anak, yang akan bernilai -1 jika tidak ada yang dipilih. Komposisi adalah susunan tata letak halaman yang dapat dibuat oleh desainer. Dengan menggunakan layer comps, Anda dapat membuat, mengelola, dan melihat beberapa versi tata letak dalam satu file Adobe® Photoshop®. Sebuah layer comp adalah snapshot dari keadaan panel Layers. Layer comps menyimpan tiga jenis opsi layer tetapi properti ini mendapatkan identifier pemilihan Layer Comp untuk Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


Mendapatkan atau mengatur properti ContentID. Nilai properti ini dibaca dan disimpan hanya ketika Versi >= 8.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


Mendapatkan atau mengatur pembuat file dalam sumber daya format PSD LnkE / Lnk2.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah sumber data tautan ini memiliki deskriptor file terbuka: CompId dan OriginalCompId.

Nilai:  true  jika instance ini memiliki deskriptor file terbuka; selainnya,  false .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Mendapatkan atau mengatur tipe file tersemat atau eksternal yang dimiliki atau ditautkan oleh sumber daya Adobe® Photoshop® Lnk2 / LnkE.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


Mendapatkan atau mengatur array OSTypeStructure yang mendefinisikan properti sumber daya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


Mendapatkan nilai yang menunjukkan apakah sumber data tautan PSD ini menautkan ke item Perpustakaan Adobe® Photoshop® \u0421\u0421.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


Mendapatkan ID asli dari Comp yang saat ini dipilih untuk dokumen anak, yang akan bernilai -1 jika tidak ada yang dipilih. Properti ini mendapatkan identifier pemilihan layer Comp asli untuk Smart Objects.  Layer comps in Smart Objects

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Mendapatkan nama file asli dari sumber data dalam sumber daya tautan global Adobe® Photoshop®.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Mengatur nilai properti berdasarkan struktur tipe.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Struktur. |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


Mendapatkan pengenal unik global dari sumber data dalam sumber daya tautan PSD.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Mendapatkan atau mengatur data tidak dikenal yang berada sebelum properti Items OSTypeStructures.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] |  |

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

