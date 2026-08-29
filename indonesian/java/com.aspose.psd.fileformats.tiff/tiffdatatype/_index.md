---
title: "TiffDataType"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Tipe data tiff."
type: docs
weight: 10
url: /id/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

Tipe data tiff.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | Membandingkan instance saat ini dengan objek lain dengan tipe yang sama dan mengembalikan sebuah integer yang menunjukkan apakah instance saat ini mendahului, mengikuti, atau berada pada posisi yang sama dalam urutan penyortiran dibandingkan dengan objek lain. |
| [deepClone()](#deepClone--) | Melakukan kloning mendalam pada instance ini. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | Mendapatkan ukuran data tambahan dalam byte (jika 12 byte tidak cukup untuk menampung data tag). |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Mendapatkan jumlah elemen. |
| [getDataSize()](#getDataSize--) | Mendapatkan ukuran data tambahan dalam byte (jika 12 byte tidak cukup untuk menampung data tag). |
| [getId()](#getId--) | Mendapatkan representasi integer dari id tag. |
| [getTagId()](#getTagId--) | Mendapatkan id tag. |
| [getTagType()](#getTagType--) | Mendapatkan tipe tag. |
| [getValue()](#getValue--) | Mendapatkan nilai yang dimiliki tipe data ini. |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | Mendapatkan nilai yang menunjukkan apakah tag bersifat pribadi. |
| [isValid()](#isValid--) | Mendapatkan nilai yang menunjukkan apakah data tag valid. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Membaca data tag. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Mengatur nilai yang dimiliki tipe data ini. |
| [toString()](#toString--) | Mengembalikan sebuah  System.String  yang mewakili instance ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | Menulis data tag tambahan. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Menulis data tag. |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Membandingkan instance saat ini dengan objek lain dengan tipe yang sama dan mengembalikan sebuah integer yang menunjukkan apakah instance saat ini mendahului, mengikuti, atau berada pada posisi yang sama dalam urutan penyortiran dibandingkan dengan objek lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Objek untuk dibandingkan dengan instance ini. |

**Returns:**
int - Integer bertanda 32-bit yang menunjukkan urutan relatif dari objek-objek yang dibandingkan. Nilai kembali memiliki arti berikut: Nilai Makna Kurang dari nol Instance ini kurang dari obj. Nol Instance ini sama dengan obj. Lebih dari nol Instance ini lebih besar dari obj.
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Melakukan kloning mendalam pada instance ini.

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


Mendapatkan ukuran data tambahan dalam byte (jika 12 byte tidak cukup untuk menampung data tag).

**Returns:**
long - Ukuran data tambahan dalam byte.

Ini adalah jumlah byte data yang diselaraskan ke batas kata.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract long getCount()
```


Mendapatkan jumlah elemen.

**Returns:**
long - Jumlah elemen.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


Mendapatkan ukuran data tambahan dalam byte (jika 12 byte tidak cukup untuk menampung data tag).

**Returns:**
long - Ukuran data tambahan dalam byte.

Ini adalah jumlah byte yang tepat.
### getId() {#getId--}
```
public int getId()
```


Mendapatkan representasi integer dari id tag.

**Returns:**
int - Representasi integer dari id tag
### getTagId() {#getTagId--}
```
public int getTagId()
```


Mendapatkan id tag.

**Returns:**
int - Id tag.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Mendapatkan tipe tag.

**Returns:**
int - Tipe tag.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Mendapatkan nilai yang dimiliki tipe data ini.

**Returns:**
java.lang.Object - Nilai.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isPrivate_internalized() {#isPrivate-internalized--}
```
public boolean isPrivate_internalized()
```


Mendapatkan nilai yang menunjukkan apakah tag bersifat pribadi. Tag tiff pribadi adalah tag dengan id tag di atas 32768.

**Returns:**
boolean -  true  jika data tag valid; jika tidak,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Mendapatkan nilai yang menunjukkan apakah data tag valid. Tag yang valid berisi data yang dapat dipertahankan. Tag yang tidak valid tidak dapat disimpan.

**Returns:**
boolean -  true  jika data tag valid; jika tidak,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Membaca data tag.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | Aliran data. |
| position | long | Posisi tag. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Mengatur nilai yang dimiliki tipe data ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Object | Nilai. |

### toString() {#toString--}
```
public String toString()
```


Mengembalikan sebuah  System.String  yang mewakili instance ini.

**Returns:**
java.lang.String - Sebuah  System.String  yang mewakili instance ini.
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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Menulis data tag tambahan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Aliran data. |

**Returns:**
long - Byte sebenarnya yang ditulis.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Menulis data tag.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Aliran data. |
| additionalDataOffset | long | Offset untuk menulis data tambahan ke. |

