---
title: "XmpPacketWrapper"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Bevat geserialiseerd xmp-pakket inclusief header en trailer."
type: docs
weight: 20
url: /nl/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

Bevat geserialiseerd xmp-pakket inclusief header en trailer.

Een wrapper bestaande uit een paar XML-verwerkingsinstructies (PIs) kan rond het rdf:RDF‑element worden geplaatst.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | Initialiseert een nieuw exemplaar van de  XmpPacketWrapper  klasse. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Initialiseert een nieuw exemplaar van de  XmpPacketWrapper  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | Voegt het pakket toe. |
| [clearPackages()](#clearPackages--) | Verwijdert alle  XmpPackage  binnen XMP. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Bepaalt of het pakket bestaat in de xmp-wrapper. |
| [deepClone_internalized()](#deepClone-internalized--) | Kloont deze instantie. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | Haalt de header‑verwerkingsinstructie op. |
| [getMeta()](#getMeta--) | Haalt de XMP‑meta op. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Haalt pakket op op basis van namespace‑URI. |
| [getPackages()](#getPackages--) | Haalt array van  XmpPackage  binnen XMP op. |
| [getPackagesCount()](#getPackagesCount--) | Haalt het aantal pakketten binnen de XMP‑structuur op. |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | Haalt het root‑RDF‑element op. |
| [getTrailerPi()](#getTrailerPi--) | Haalt de trailer‑verwerkingsinstructie op. |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | Converteert XMP-waarde naar de XML-representatie. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | Verwijdert het XMP‑pakket. |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | Stelt de header‑verwerkingsinstructie in. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | Stelt de XMP‑meta in. |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | Stelt het root‑RDF‑element in. |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | Stelt de trailer‑verwerkingsinstructie in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Initialiseert een nieuw exemplaar van de  XmpPacketWrapper  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | De XMP-header van de verwerkingsinstructie. |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | De XMP-trailer van de verwerkingsinstructie. |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | De XMP-metadata. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Initialiseert een nieuw exemplaar van de  XmpPacketWrapper  klasse.

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Voegt het pakket toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Het pakket. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Verwijdert alle  XmpPackage  binnen XMP.

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Bepaalt of het pakket bestaat in de xmp-wrapper.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| namespaceUri | java.lang.String | Pakket‑schema‑uri. |

**Returns:**
boolean - Retourneert true als een pakket met de opgegeven namespace‑uri bestaat in de XMP-wrapper.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


Kloont deze instantie.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de header‑verwerkingsinstructie op.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Haalt de XMP‑meta op. Optioneel.

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Haalt pakket op op basis van namespace‑URI.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| namespaceUri | java.lang.String | De pakket‑schema‑URI. |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Haalt array van  XmpPackage  binnen XMP op.

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - De array van XmpPackage binnen XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Haalt het aantal pakketten binnen de XMP‑structuur op.

**Returns:**
int - Het aantal pakketten binnen de XMP-structuur.
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


Haalt het root‑RDF‑element op.

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Haalt de trailer‑verwerkingsinstructie op.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


Converteert XMP-waarde naar de XML-representatie.

**Returns:**
java.lang.String - Retourneert de geconverteerde XMP-waarde naar XML.
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


Verwijdert het XMP‑pakket.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Het pakket. |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


Stelt de header‑verwerkingsinstructie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | De Header-verwerkingsinstructie. |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Stelt de XMP‑meta in. Optioneel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | De XMP‑meta. Optioneel. |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


Stelt het root‑RDF‑element in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | Het RDF‑hoofdelement. |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


Stelt de trailer‑verwerkingsinstructie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Trailer‑verwerkingsinstructie. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

