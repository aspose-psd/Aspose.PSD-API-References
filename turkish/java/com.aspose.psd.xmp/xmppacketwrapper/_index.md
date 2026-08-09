---
title: "XmpPacketWrapper"
second_title: "Java için Aspose.PSD API Referansı"
description: "Başlık ve kuyruk dahil olmak üzere serileştirilmiş xmp paketini içerir."
type: docs
weight: 20
url: /tr/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

Başlık ve kuyruk dahil olmak üzere serileştirilmiş xmp paketini içerir.

XML işleme talimatlarından (PI'ler) oluşan bir çift içeren bir sarmalayıcı, rdf:RDF öğesinin etrafına yerleştirilebilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | XmpPacketWrapper sınıfının yeni bir örneğini başlatır. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | XmpPacketWrapper sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | Paketi ekler. |
| [clearPackages()](#clearPackages--) | XMP içindeki tüm XmpPackage'ları kaldırır. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Paketin xmp sarmalayıcı içinde mevcut olup olmadığını belirler. |
| [deepClone_internalized()](#deepClone-internalized--) | Bu örneği klonlar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | Başlık işleme talimatını alır. |
| [getMeta()](#getMeta--) | XMP meta verisini alır. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Paket'i ad alanı URI'sine göre alır. |
| [getPackages()](#getPackages--) | XMP içindeki XmpPackage dizisini alır. |
| [getPackagesCount()](#getPackagesCount--) | XMP yapısı içindeki paket sayısını alır. |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | Kök RDF öğesini alır. |
| [getTrailerPi()](#getTrailerPi--) | Sonek işleme talimatını alır. |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | XMP değerini XML temsiline dönüştürür. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | XMP paketini kaldırır. |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | Başlık işleme talimatını ayarlar. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | XMP meta verisini ayarlar. |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | Kök RDF öğesini ayarlar. |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | Sonek işleme talimatını ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


XmpPacketWrapper sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | İşleme talimatının XMP başlığı. |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | İşleme talimatının XMP soneki. |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | XMP meta verileri. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


XmpPacketWrapper sınıfının yeni bir örneğini başlatır.

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Paketi ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Paket. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


XMP içindeki tüm XmpPackage'ları kaldırır.

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Paketin xmp sarmalayıcı içinde mevcut olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| namespaceUri | java.lang.String | Paket şema URI'si. |

**Returns:**
boolean - Belirtilen namespace Uri'ye sahip paket XMP sarmalayıcısında mevcutsa true döndürür.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


Bu örneği klonlar.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
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
### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Başlık işleme talimatını alır.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


XMP meta verisini alır. İsteğe bağlı.

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Paket'i ad alanı URI'sine göre alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| namespaceUri | java.lang.String | Paket şema URI'si. |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


XMP içindeki XmpPackage dizisini alır.

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - XMP içinde bulunan XmpPackage dizisi.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


XMP yapısı içindeki paket sayısını alır.

**Returns:**
int - XMP yapısı içinde bulunan paket sayısı.
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


Kök RDF öğesini alır.

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Sonek işleme talimatını alır.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


XMP değerini XML temsiline dönüştürür.

**Returns:**
java.lang.String - Dönüştürülmüş XMP değerini XML'e döndürür.
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


XMP paketini kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Paket. |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


Başlık işleme talimatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Başlık işleme talimatı. |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


XMP meta verisini ayarlar. İsteğe bağlı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | XMP meta verisi. İsteğe bağlı. |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


Kök RDF öğesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | RDF kök öğesi. |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


Sonek işleme talimatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Trailer işleme talimatı. |

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

