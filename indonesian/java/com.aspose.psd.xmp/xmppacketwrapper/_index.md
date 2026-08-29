---
title: "XmpPacketWrapper"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Berisi paket xmp yang diserialkan termasuk header dan trailer."
type: docs
weight: 20
url: /id/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

Berisi paket xmp yang diserialkan termasuk header dan trailer.

Sebuah wrapper yang terdiri dari sepasang instruksi pemrosesan XML (PI) dapat ditempatkan di sekitar elemen rdf:RDF.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | Menginisialisasi sebuah instance baru dari kelas  XmpPacketWrapper  . |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Menginisialisasi sebuah instance baru dari kelas  XmpPacketWrapper  . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | Menambahkan paket. |
| [clearPackages()](#clearPackages--) | Menghapus semua  XmpPackage  di dalam XMP. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Menentukan apakah paket ada dalam wrapper XMP. |
| [deepClone_internalized()](#deepClone-internalized--) | Mengkloning instance ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | Mendapatkan instruksi pemrosesan header. |
| [getMeta()](#getMeta--) | Mendapatkan meta XMP. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Mendapatkan paket berdasarkan URI namespace. |
| [getPackages()](#getPackages--) | Mendapatkan array dari  XmpPackage  di dalam XMP. |
| [getPackagesCount()](#getPackagesCount--) | Mendapatkan jumlah paket di dalam struktur XMP. |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | Mendapatkan elemen RDF root. |
| [getTrailerPi()](#getTrailerPi--) | Mendapatkan instruksi pemrosesan trailer. |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | Mengonversi nilai XMP ke representasi XML. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | Menghapus paket XMP. |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | Mengatur instruksi pemrosesan header. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | Mengatur meta XMP. |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | Mengatur elemen RDF root. |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | Mengatur instruksi pemrosesan trailer. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Menginisialisasi sebuah instance baru dari kelas  XmpPacketWrapper  .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Header XMP dari instruksi pemrosesan. |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Trailer XMP dari instruksi pemrosesan. |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Metadata XMP. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Menginisialisasi sebuah instance baru dari kelas  XmpPacketWrapper  .

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Menambahkan paket.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Paket. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Menghapus semua  XmpPackage  di dalam XMP.

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Menentukan apakah paket ada dalam wrapper XMP.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI skema paket. |

**Returns:**
boolean - Mengembalikan true jika paket dengan namespace Uri yang ditentukan ada dalam pembungkus XMP.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


Mengkloning instance ini.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
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
### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Mendapatkan instruksi pemrosesan header.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Mendapatkan meta XMP. Opsional.

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Mendapatkan paket berdasarkan URI namespace.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI skema paket. |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Mendapatkan array dari  XmpPackage  di dalam XMP.

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - Array dari XmpPackage di dalam XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Mendapatkan jumlah paket di dalam struktur XMP.

**Returns:**
int - Jumlah paket di dalam struktur XMP.
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


Mendapatkan elemen RDF root.

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Mendapatkan instruksi pemrosesan trailer.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


Mengonversi nilai XMP ke representasi XML.

**Returns:**
java.lang.String - Mengembalikan nilai XMP yang dikonversi ke XML.
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




### removePackage(XmpPackage package_) {#removePackage-com.aspose.psd.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Menghapus paket XMP.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Paket. |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


Mengatur instruksi pemrosesan header.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Instruksi pemrosesan Header. |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Mengatur meta XMP. Opsional.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Meta XMP. Opsional. |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


Mengatur elemen RDF root.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | Elemen akar RDF. |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


Mengatur instruksi pemrosesan trailer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Instruksi pemrosesan Trailer. |

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

