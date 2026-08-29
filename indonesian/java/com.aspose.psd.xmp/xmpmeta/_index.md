---
title: "XmpMeta"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili xmpmeta."
type: docs
weight: 17
url: /id/java/com.aspose.psd.xmp/xmpmeta/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Mewakili xmpmeta. Opsional. Tujuan elemen ini adalah untuk mengidentifikasi metadata XMP dalam teks XML umum yang mungkin berisi penggunaan RDF non-XMP lainnya.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Menginisialisasi sebuah instance baru dari kelas  XmpMeta . |
| [XmpMeta()](#XmpMeta--) | Menginisialisasi sebuah instance baru dari kelas  XmpMeta . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Menambahkan atribut. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Menetapkan elemen XMP yang ditentukan ke yang saat ini. |
| [clearAttributes()](#clearAttributes--) | Menghapus semua atribut. |
| [deepClone_internalized()](#deepClone-internalized--) | Mengkloning instance ini. |
| [equals(Object other)](#equals-java.lang.Object-) | Menentukan apakah System.Object yang ditentukan, sama dengan instance ini. |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Mendapatkan atau mengatur versi toolkit Adobe Xmp. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Mendapatkan atribut. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | Mengonversi nilai XMP ke representasi XML. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Menunjukkan apakah objek saat ini sama dengan objek lain dari tipe yang sama. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.psd.xmp.XmpMeta-) | Menunjukkan apakah objek saat ini sama dengan objek lain dari tipe yang sama. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Mendapatkan atau mengatur versi toolkit Adobe Xmp. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Menginisialisasi sebuah instance baru dari kelas  XmpMeta .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Versi toolkit Adobe XMP. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Menginisialisasi sebuah instance baru dari kelas  XmpMeta .

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Menambahkan atribut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| attribute | java.lang.String | Atribut. |
| nilai | java.lang.String | Nilai. |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


Menetapkan elemen XMP yang ditentukan ke yang saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Elemen XMP. |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Menghapus semua atribut.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


Mengkloning instance ini.

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Menentukan apakah System.Object yang ditentukan, sama dengan instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lainnya | java.lang.Object | System.Object yang akan dibandingkan dengan instance ini. |

**Returns:**
boolean - true jika System.Object yang ditentukan sama dengan instance ini; jika tidak, false.
### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Mendapatkan atau mengatur versi toolkit Adobe Xmp.

**Returns:**
java.lang.String
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Mendapatkan atribut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| attribute | java.lang.String | Atribut. |

**Returns:**
java.lang.String - Mengembalikan atribut untuk nama atribut yang ditentukan.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Mengonversi nilai XMP ke representasi XML.

**Returns:**
java.lang.String - Mengembalikan nilai XMP yang dikonversi ke representasi XML.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini.

**Returns:**
int - Kode hash untuk instance ini, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash.
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Menunjukkan apakah objek saat ini sama dengan objek lain dari tipe yang sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Objek untuk dibandingkan dengan objek ini. |

**Returns:**
boolean - true jika objek saat ini sama dengan parameter other; jika tidak, false.
### isEquals(XmpMeta other) {#isEquals-com.aspose.psd.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Menunjukkan apakah objek saat ini sama dengan objek lain dari tipe yang sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Objek untuk dibandingkan dengan objek ini. |

**Returns:**
boolean - true jika objek saat ini sama dengan parameter other; jika tidak, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Mendapatkan atau mengatur versi toolkit Adobe Xmp.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

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

