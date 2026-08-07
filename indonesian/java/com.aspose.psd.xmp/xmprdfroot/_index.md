---
title: "XmpRdfRoot"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili elemen rdfRDF."
type: docs
weight: 21
url: /id/java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Mewakili elemen rdf:RDF. Sebuah paket XMP tunggal harus diserialisasi menggunakan satu elemen XML rdf:RDF. Konten elemen rdf:RDF hanya boleh terdiri dari nol atau lebih elemen rdf:Description.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Menginisialisasi instance baru dari kelas XmpRdfRoot. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Menambahkan atribut. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Menetapkan elemen XMP yang ditentukan ke yang saat ini. |
| [clearAttributes()](#clearAttributes--) | Menghapus semua atribut. |
| [deepClone_internalized()](#deepClone-internalized--) | Mengkloning instance ini. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah Object yang ditentukan, sama dengan instance ini. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Mendapatkan atribut. |
| [getClass()](#getClass--) |  |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Mendapatkan URI namespace berdasarkan prefiks tertentu. |
| [getXmlValue()](#getXmlValue--) | Mengonversi nilai xmp ke representasi xml. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Menunjukkan apakah objek saat ini sama dengan objek lain dari tipe yang sama. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Menambahkan URI namespace dengan prefiks. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Menginisialisasi instance baru dari kelas XmpRdfRoot.

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
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah Object yang ditentukan, sama dengan instance ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Object yang akan dibandingkan dengan instance ini. |

**Returns:**
boolean -  true  jika Object yang ditentukan sama dengan instance ini; jika tidak,  false .
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
### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Mendapatkan URI namespace berdasarkan prefiks tertentu. Prefiks dapat dimulai tanpa xmlns.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| awalan | java.lang.String | Awalan. |

**Returns:**
java.lang.String - Mengembalikan URI skema paket.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Mengonversi nilai xmp ke representasi xml.

**Returns:**
java.lang.String - Mengembalikan nilai XMP yang dikonversi menjadi string XML.
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Menambahkan URI namespace dengan prefiks. Prefiks dapat dimulai tanpa xmlns.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| awalan | java.lang.String | Awalan. |
| namespaceUri | java.lang.String | URI skema paket. |

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

