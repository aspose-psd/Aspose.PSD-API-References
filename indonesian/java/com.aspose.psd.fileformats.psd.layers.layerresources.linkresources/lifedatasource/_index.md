---
title: "LiFeDataSource"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mendefinisikan kelas LnkeDataSource yang berisi informasi tentang file tautan eksternal."
type: docs
weight: 11
url: /id/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFeDataSource extends LinkDataSource
```

Mendefinisikan kelas LnkeDataSource yang berisi informasi tentang file eksternal yang ditautkan. Ini merupakan bagian dari API Manipulasi Format File PSD yang membantu memodifikasi file Adobe® Photoshop®.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LiFeDataSource()](#LiFeDataSource--) | Menginisialisasi instance baru dari kelas [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). |
| [LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | Menginisialisasi instance baru dari kelas [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource). |
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
| [create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeStockId()](#getAdobeStockId--) | Mendapatkan atau mengatur AdobeStockId perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries. |
| [getAdobeStockLicenseState()](#getAdobeStockLicenseState--) | Mendapatkan status lisensi adobe stock jika tersedia, untuk Adobe® Photoshop® CC libraries. |
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
| [getDate()](#getDate--) | Mendapatkan atau mengatur tanggal dan waktu penulisan terakhir dari file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE. |
| [getDate_internalized()](#getDate-internalized--) |  |
| [getElementName()](#getElementName--) | Mendapatkan atau mengatur nama elemen perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries. |
| [getElementRef()](#getElementRef--) | Mendapatkan atau mengatur referensi elemen perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries. |
| [getFileCreator()](#getFileCreator--) | Mendapatkan atau mengatur pembuat file dalam sumber daya format PSD LnkE / Lnk2. |
| [getFileName()](#getFileName--) | Mendapatkan atau mengatur nama file eksternal atau tersemat dalam sumber daya tautan PSD. |
| [getFileSize()](#getFileSize--) | Mendapatkan atau mengatur ukuran file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE. |
| [getFileType()](#getFileType--) | Mendapatkan atau mengatur tipe file tersemat atau eksternal yang dimiliki atau ditautkan oleh sumber daya Adobe® Photoshop® Lnk2 / LnkE. |
| [getFullPath()](#getFullPath--) | Mendapatkan atau mengatur jalur lengkap file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE. |
| [getItems_internalized()](#getItems-internalized--) | Mendapatkan atau mengatur array OSTypeStructure yang mendefinisikan properti sumber daya. |
| [getLength()](#getLength--) | Mendapatkan panjang sumber data tautan dalam byte. |
| [getOriginalCompId()](#getOriginalCompId--) | Mendapatkan ID asli dari Comp yang saat ini dipilih untuk dokumen anak, yang akan menjadi -1 jika tidak ada yang dipilih. |
| [getOriginalFileName()](#getOriginalFileName--) | Mendapatkan nama file asli dari sumber data dalam sumber daya tautan global Adobe® Photoshop®. |
| [getRelativePath()](#getRelativePath--) | Mendapatkan atau mengatur jalur relatif file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE. |
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
| [setAdobeStockId(String value)](#setAdobeStockId-java.lang.String-) | Mendapatkan atau mengatur AdobeStockId perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries. |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah aset PSD terkunci. |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Mendapatkan atau mengatur waktu modifikasi aset, untuk aset Adobe® Photoshop® \\u0421\\u0421 Libraries. |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Mendapatkan atau mengatur pengidentifikasi dokumen anak dalam sumber data liFE atau liFD dari sumber daya Lnk2 / LnkE Adobe® Photoshop®. |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Mendapatkan atau mengatur id kelas sumber daya. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Mendapatkan atau mengatur nama kelas sumber daya. |
| [setCompId(int value)](#setCompId-int-) | Mendapatkan atau mengatur ID komponen yang saat ini dipilih untuk dokumen anak, yang akan menjadi -1 jika tidak ada yang dipilih. |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | Mendapatkan atau mengatur properti ContentID. |
| [setDate(Date value)](#setDate-java.util.Date-) | Mendapatkan atau mengatur tanggal dan waktu penulisan terakhir dari file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE. |
| [setDate_internalized(System.DateTime value)](#setDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setElementName(String value)](#setElementName-java.lang.String-) | Mendapatkan atau mengatur nama elemen perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries. |
| [setElementRef(String value)](#setElementRef-java.lang.String-) | Mendapatkan atau mengatur referensi elemen perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries. |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | Mendapatkan atau mengatur pembuat file dalam sumber daya format PSD LnkE / Lnk2. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Mendapatkan atau mengatur nama file eksternal atau tersemat dalam sumber daya tautan PSD. |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah sumber data tautan ini memiliki deskriptor file terbuka: CompId dan OriginalCompId. |
| [setFileSize(long value)](#setFileSize-long-) | Mendapatkan atau mengatur ukuran file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE. |
| [setFileType(String value)](#setFileType-java.lang.String-) | Mendapatkan atau mengatur tipe file tersemat atau eksternal yang dimiliki atau ditautkan oleh sumber daya Adobe® Photoshop® Lnk2 / LnkE. |
| [setFullPath(String value)](#setFullPath-java.lang.String-) | Mendapatkan atau mengatur jalur lengkap file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE. |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Mendapatkan atau mengatur array OSTypeStructure yang mendefinisikan properti sumber daya. |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | Mendapatkan nilai yang menunjukkan apakah sumber data tautan PSD ini menautkan ke item Perpustakaan Adobe® Photoshop® \u0421\u0421. |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | Mendapatkan ID asli dari Comp yang saat ini dipilih untuk dokumen anak, yang akan menjadi -1 jika tidak ada yang dipilih. |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Mendapatkan nama file asli dari sumber data dalam sumber daya tautan global Adobe® Photoshop®. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Mengatur nilai properti berdasarkan struktur tipe. |
| [setRelativePath(String value)](#setRelativePath-java.lang.String-) | Mendapatkan atau mengatur jalur relatif file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE. |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | Mendapatkan pengenal unik global dari sumber data dalam sumber daya tautan PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Mendapatkan atau mengatur data tidak dikenal yang berada sebelum properti Items OSTypeStructures. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFeDataSource() {#LiFeDataSource--}
```
public LiFeDataSource()
```


Menginisialisasi instance baru dari kelas [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).

### LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


Menginisialisasi instance baru dari kelas [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| version | int | Versi. |
| uniqueId | java.util.UUID | Pengidentifikasi unik. |
| originalFileName | java.lang.String | Nama file asli. |
| fileType | java.lang.String | Tipe file. |
| fileCreator | java.lang.String | Pembuat file. |

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

### create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFeDataSource create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| version | int |  |
| uniqueId | com.aspose.ms.System.Guid |  |
| originalFileName | java.lang.String |  |
| fileType | java.lang.String |  |
| fileCreator | java.lang.String |  |

**Returns:**
[LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource)
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
### getAdobeStockId() {#getAdobeStockId--}
```
public final String getAdobeStockId()
```


Mendapatkan atau mengatur AdobeStockId perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries.

**Returns:**
java.lang.String
### getAdobeStockLicenseState() {#getAdobeStockLicenseState--}
```
public final String getAdobeStockLicenseState()
```


Mendapatkan status lisensi adobe stock jika tersedia, untuk Adobe® Photoshop® CC libraries.

Nilai: Status lisensi adobe stock atau string kosong jika tidak tersedia.

**Returns:**
java.lang.String
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
### getDate() {#getDate--}
```
public final Date getDate()
```


Mendapatkan atau mengatur tanggal dan waktu penulisan terakhir dari file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE.

**Returns:**
java.util.Date
### getDate_internalized() {#getDate-internalized--}
```
public final System.DateTime getDate_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getElementName() {#getElementName--}
```
public final String getElementName()
```


Mendapatkan atau mengatur nama elemen perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries.

**Returns:**
java.lang.String
### getElementRef() {#getElementRef--}
```
public final String getElementRef()
```


Mendapatkan atau mengatur referensi elemen perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries.

**Returns:**
java.lang.String
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


Mendapatkan atau mengatur pembuat file dalam sumber daya format PSD LnkE / Lnk2.

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Mendapatkan atau mengatur nama file eksternal atau tersemat dalam sumber daya tautan PSD.

Nilai: Nama file eksternal atau tersemat.

**Returns:**
java.lang.String
### getFileSize() {#getFileSize--}
```
public final long getFileSize()
```


Mendapatkan atau mengatur ukuran file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE.

**Returns:**
long
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Mendapatkan atau mengatur tipe file tersemat atau eksternal yang dimiliki atau ditautkan oleh sumber daya Adobe® Photoshop® Lnk2 / LnkE.

**Returns:**
java.lang.String
### getFullPath() {#getFullPath--}
```
public final String getFullPath()
```


Mendapatkan atau mengatur jalur lengkap file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE.

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
### getRelativePath() {#getRelativePath--}
```
public final String getRelativePath()
```


Mendapatkan atau mengatur jalur relatif file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE.

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

### setAdobeStockId(String value) {#setAdobeStockId-java.lang.String-}
```
public final void setAdobeStockId(String value)
```


Mendapatkan atau mengatur AdobeStockId perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

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

### setDate(Date value) {#setDate-java.util.Date-}
```
public final void setDate(Date value)
```


Mendapatkan atau mengatur tanggal dan waktu penulisan terakhir dari file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

### setDate_internalized(System.DateTime value) {#setDate-internalized-com.aspose.ms.System.DateTime-}
```
public final void setDate_internalized(System.DateTime value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.ms.System.DateTime |  |

### setElementName(String value) {#setElementName-java.lang.String-}
```
public final void setElementName(String value)
```


Mendapatkan atau mengatur nama elemen perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setElementRef(String value) {#setElementRef-java.lang.String-}
```
public final void setElementRef(String value)
```


Mendapatkan atau mengatur referensi elemen perpustakaan grafis, untuk Adobe® Photoshop® CC Libraries.

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

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


Mendapatkan atau mengatur nama file eksternal atau tersemat dalam sumber daya tautan PSD.

Nilai: Nama file eksternal atau tersemat.

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

### setFileSize(long value) {#setFileSize-long-}
```
public final void setFileSize(long value)
```


Mendapatkan atau mengatur ukuran file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Mendapatkan atau mengatur tipe file tersemat atau eksternal yang dimiliki atau ditautkan oleh sumber daya Adobe® Photoshop® Lnk2 / LnkE.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### setFullPath(String value) {#setFullPath-java.lang.String-}
```
public final void setFullPath(String value)
```


Mendapatkan atau mengatur jalur lengkap file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE.

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

### setRelativePath(String value) {#setRelativePath-java.lang.String-}
```
public final void setRelativePath(String value)
```


Mendapatkan atau mengatur jalur relatif file eksternal dalam sumber data LiFE pada sumber daya PSD LnkE.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

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

