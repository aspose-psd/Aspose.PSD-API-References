---
title: "XmpDate"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili Tanggal dalam paket XMP."
type: docs
weight: 11
url: /id/java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Mewakili Tanggal dalam paket XMP.

Nilai tanggal-waktu direpresentasikan menggunakan subset format seperti yang didefinisikan dalam Format Tanggal dan Waktu: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Menginisialisasi instance baru dari kelas  XmpDate  . |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Menginisialisasi instance baru dari kelas  XmpDate  . |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | String format ISO 8601 (roundtrip). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | Mendapatkan string format untuk nilai saat ini. |
| [getValue()](#getValue--) | Mendapatkan atau mengatur nilai tanggal. |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | Mengembalikan nilai string yang terkandung dalam format XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | Mendapatkan atau mengatur nilai tanggal. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Menginisialisasi instance baru dari kelas  XmpDate  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dateTime | java.util.Date | Nilai tanggal-waktu yang direpresentasikan menggunakan subset format ISO RFC 8601. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Menginisialisasi instance baru dari kelas  XmpDate  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dateString | java.lang.String | Representasi string dari tanggal. |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


String format ISO 8601 (roundtrip).

Lihat selengkapnya: https://en.wikipedia.org/wiki/ISO\_8601.

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
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
### getFormat() {#getFormat--}
```
public String getFormat()
```


Mendapatkan string format untuk nilai saat ini.

Nilai: String format untuk nilai saat ini.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


Mendapatkan atau mengatur nilai tanggal.

Nilai: Nilai tanggal.

**Returns:**
java.util.Date
### getValue_internalized() {#getValue-internalized--}
```
public System.DateTime getValue_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Mengembalikan nilai string yang terkandung dalam format XMP.

**Returns:**
java.lang.String - Mengembalikan nilai string yang terkandung dalam format XMP.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Mendapatkan atau mengatur nilai tanggal.

Nilai: Nilai tanggal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.util.Date |  |

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

