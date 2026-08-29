---
title: "XmpRdfRoot"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar rdfRDF-elementet."
type: docs
weight: 21
url: /sv/java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Representerar rdf:RDF-elementet. Ett enskilt XMP-paket ska serialiseras med ett enda rdf:RDF XML-element. Innehållet i rdf:RDF-elementet ska bestå av noll eller fler rdf:Description-element.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Initierar en ny instans av klassen  XmpRdfRoot  . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Lägger till attributet. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Tilldelar det angivna XMP-elementet till det aktuella. |
| [clearAttributes()](#clearAttributes--) | Tar bort alla attribut. |
| [deepClone_internalized()](#deepClone-internalized--) | Klonar den här instansen. |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om det angivna  Object , är lika med denna instans. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Hämtar attributet. |
| [getClass()](#getClass--) |  |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Hämtar namnrymds-URI för en specifik prefix. |
| [getXmlValue()](#getXmlValue--) | Konverterar xmp‑värde till xml‑representationen. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för den här instansen. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Anger om det aktuella objektet är lika med ett annat objekt av samma typ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Lägger till namnrymds-URI med prefix. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Initierar en ny instans av klassen  XmpRdfRoot  .

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Lägger till attributet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| attribut | java.lang.String | Attributet. |
| värde | java.lang.String | Värdet. |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


Tilldelar det angivna XMP-elementet till det aktuella.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | XMP-elementet. |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Tar bort alla attribut.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


Klonar den här instansen.

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Avgör om det angivna  Object , är lika med denna instans.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det  Object  att jämföra med den här instansen. |

**Returns:**
boolean -  true  om det angivna  Object  är lika med den här instansen; annars,  false .
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Hämtar attributet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| attribut | java.lang.String | Attributet. |

**Returns:**
java.lang.String - Returnerar attributet för angivet attributnamn.
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


Hämtar namnrymds-URI för en specifik prefix. Prefix kan börja utan xmlns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | java.lang.String | Prefixet. |

**Returns:**
java.lang.String - Returnerar ett paketets schema-URI.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konverterar xmp‑värde till xml‑representationen.

**Returns:**
java.lang.String - Returnerar XMP-värdet konverterat till XML-sträng.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för den här instansen.

**Returns:**
int - En hashkod för den här instansen, lämplig för användning i hash‑algoritmer och datastrukturer som en hashtabell.
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Anger om det aktuella objektet är lika med ett annat objekt av samma typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Ett objekt att jämföra med detta objekt. |

**Returns:**
boolean - true om det aktuella objektet är lika med  other  parametern; annars false.
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


Lägger till namnrymds-URI med prefix. Prefix kan börja utan xmlns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | java.lang.String | Prefixet. |
| namespaceUri | java.lang.String | Paketets schema‑URI. |

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

