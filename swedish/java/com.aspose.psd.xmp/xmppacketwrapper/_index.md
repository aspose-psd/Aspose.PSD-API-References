---
title: "XmpPacketWrapper"
second_title: "Aspose.PSD för Java API-referens"
description: "Innehåller serialiserat xmp-paket inklusive header och trailer."
type: docs
weight: 20
url: /sv/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

Innehåller serialiserat xmp-paket inklusive header och trailer.

En omslag bestående av ett par XML‑processinstruktioner (PI) kan placeras runt rdf:RDF‑elementet.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | Initierar en ny instans av klassen  XmpPacketWrapper . |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Initierar en ny instans av klassen  XmpPacketWrapper . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | Lägger till paketet. |
| [clearPackages()](#clearPackages--) | Tar bort alla  XmpPackage  i XMP. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Bestämmer om paketet finns i xmp wrapper. |
| [deepClone_internalized()](#deepClone-internalized--) | Klonar den här instansen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | Hämtar header‑processinstruktionen. |
| [getMeta()](#getMeta--) | Hämtar XMP‑meta. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Hämtar paketet efter namnrymds‑URI. |
| [getPackages()](#getPackages--) | Hämtar array av  XmpPackage  i XMP. |
| [getPackagesCount()](#getPackagesCount--) | Hämtar antalet paket i XMP‑strukturen. |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | Hämtar rot‑RDF‑elementet. |
| [getTrailerPi()](#getTrailerPi--) | Hämtar trailer‑processinstruktionen. |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | Konverterar XMP‑värdet till XML‑representationen. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | Tar bort XMP‑paketet. |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | Ställer in header‑processinstruktionen. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | Ställer in XMP‑meta. |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | Ställer in rot‑RDF‑elementet. |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | Ställer in trailer‑processinstruktionen. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Initierar en ny instans av klassen  XmpPacketWrapper .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | XMP‑headern för processinstruktionen. |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | XMP‑trailern för processinstruktionen. |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | XMP-metadata. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Initierar en ny instans av klassen  XmpPacketWrapper .

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Lägger till paketet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Paketet. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Tar bort alla  XmpPackage  i XMP.

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Bestämmer om paketet finns i xmp wrapper.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namespaceUri | java.lang.String | Paketets schema‑URI. |

**Returns:**
boolean - Returnerar true om paket med angiven namnrymds‑URI finns i XMP‑wrapper.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


Klonar den här instansen.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar header‑processinstruktionen.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Hämtar XMP‑meta. Valfritt.

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Hämtar paketet efter namnrymds‑URI.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namespaceUri | java.lang.String | Paketets schema‑URI. |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Hämtar array av  XmpPackage  i XMP.

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - Arrayen av XmpPackage i XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Hämtar antalet paket i XMP‑strukturen.

**Returns:**
int - Antalet paket i XMP‑strukturen.
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


Hämtar rot‑RDF‑elementet.

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Hämtar trailer‑processinstruktionen.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


Konverterar XMP‑värdet till XML‑representationen.

**Returns:**
java.lang.String - Returnerar konverterat XMP‑värde till XML.
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


Tar bort XMP‑paketet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Paketet. |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


Ställer in header‑processinstruktionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Header‑processinstruktionen. |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Ställer in XMP‑metadata. Valfritt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | XMP‑metadata. Valfritt. |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


Ställer in rot‑RDF‑elementet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | RDF‑rotnoden. |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


Ställer in trailer‑processinstruktionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Trailer‑processinstruktion. |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

