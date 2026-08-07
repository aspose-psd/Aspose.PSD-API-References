---
title: "XmpPacketWrapper"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Enthält ein serialisiertes xmp-Paket einschließlich Header und Trailer."
type: docs
weight: 20
url: /de/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

Enthält ein serialisiertes xmp-Paket einschließlich Header und Trailer.

Ein Wrapper, der aus einem Paar von XML-Verarbeitungsanweisungen (PIs) besteht, kann um das rdf:RDF-Element gelegt werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | Initialisiert eine neue Instanz der  XmpPacketWrapper  Klasse. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Initialisiert eine neue Instanz der  XmpPacketWrapper  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | Fügt das Paket hinzu. |
| [clearPackages()](#clearPackages--) | Entfernt alle  XmpPackage  innerhalb von XMP. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Bestimmt, ob das Paket im XMP-Wrapper existiert. |
| [deepClone_internalized()](#deepClone-internalized--) | Klont diese Instanz. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | Ruft die Header-Verarbeitungsanweisung ab. |
| [getMeta()](#getMeta--) | Ruft die XMP-Metadaten ab. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Ruft das Paket anhand des Namespace-URI ab. |
| [getPackages()](#getPackages--) | Ruft das Array von  XmpPackage  innerhalb von XMP ab. |
| [getPackagesCount()](#getPackagesCount--) | Ruft die Anzahl der Pakete innerhalb der XMP-Struktur ab. |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | Ruft das Root-RDF-Element ab. |
| [getTrailerPi()](#getTrailerPi--) | Ruft die Trailer-Verarbeitungsanweisung ab. |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | Entfernt das XMP-Paket. |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | Setzt die Header-Verarbeitungsanweisung. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | Setzt die XMP-Metadaten. |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | Setzt das Root-RDF-Element. |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | Setzt die Trailer-Verarbeitungsanweisung. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Initialisiert eine neue Instanz der  XmpPacketWrapper  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Der XMP-Header der Verarbeitungsanweisung. |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Der XMP-Trailer der Verarbeitungsanweisung. |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Die XMP-Metadaten. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Initialisiert eine neue Instanz der  XmpPacketWrapper  Klasse.

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Fügt das Paket hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Das Paket. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Entfernt alle  XmpPackage  innerhalb von XMP.

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Bestimmt, ob das Paket im XMP-Wrapper existiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| namespaceUri | java.lang.String | Paket-Schema-URI. |

**Returns:**
boolean - Gibt true zurück, wenn ein Paket mit dem angegebenen Namespace-Uri im XMP-Wrapper existiert.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


Klont diese Instanz.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Ruft die Header-Verarbeitungsanweisung ab.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Liest die XMP-Metadaten. Optional.

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Ruft das Paket anhand des Namespace-URI ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| namespaceUri | java.lang.String | Der Paket‑Schema‑URI. |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Ruft das Array von  XmpPackage  innerhalb von XMP ab.

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - Das Array von XmpPackage innerhalb von XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Ruft die Anzahl der Pakete innerhalb der XMP-Struktur ab.

**Returns:**
int - Die Anzahl der Pakete innerhalb der XMP-Struktur.
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


Ruft das Root-RDF-Element ab.

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Ruft die Trailer-Verarbeitungsanweisung ab.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns:**
java.lang.String - Gibt den konvertierten XMP-Wert als XML zurück.
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


Entfernt das XMP-Paket.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Das Paket. |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


Setzt die Header-Verarbeitungsanweisung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Die Header-Verarbeitungsanweisung. |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Setzt die XMP-Metadaten. Optional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Die XMP-Metadaten. Optional. |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


Setzt das Root-RDF-Element.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | Das RDF-Stammelement. |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


Setzt die Trailer-Verarbeitungsanweisung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Trailer-Verarbeitungsanweisung. |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

