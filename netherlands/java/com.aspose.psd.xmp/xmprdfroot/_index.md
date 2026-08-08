---
title: "XmpRdfRoot"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt rdfRDF-element voor."
type: docs
weight: 21
url: /nl/java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Stelt rdf:RDF-element voor. Een enkel XMP-pakket moet worden geserialiseerd met een enkel rdf:RDF XML-element. De inhoud van het rdf:RDF-element mag alleen nul of meer rdf:Description-elementen bevatten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Initialiseert een nieuw exemplaar van de XmpRdfRoot-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Voegt het attribuut toe. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Wijst het opgegeven XMP-element toe aan het huidige. |
| [clearAttributes()](#clearAttributes--) | Verwijdert alle attributen. |
| [deepClone_internalized()](#deepClone-internalized--) | Kloont deze instantie. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of het opgegeven Object gelijk is aan deze instantie. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Haalt het attribuut op. |
| [getClass()](#getClass--) |  |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Haalt namespace-URI op op basis van een specifiek prefix. |
| [getXmlValue()](#getXmlValue--) | Converteert xmp‑waarde naar de xml‑representatie. |
| [hashCode()](#hashCode--) | Retourneert een hashcode voor dit exemplaar. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Geeft aan of het huidige object gelijk is aan een ander object van hetzelfde type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Voegt namespace-URI toe via prefix. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Initialiseert een nieuw exemplaar van de XmpRdfRoot-klasse.

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Voegt het attribuut toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| attribuut | java.lang.String | Het attribuut. |
| waarde | java.lang.String | De waarde. |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


Wijst het opgegeven XMP-element toe aan het huidige.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Het XMP-element. |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Verwijdert alle attributen.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


Kloont deze instantie.

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of het opgegeven Object gelijk is aan deze instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het  Object  om te vergelijken met deze instantie. |

**Returns:**
boolean -  true  als het opgegeven  Object  gelijk is aan deze instantie; anders,  false .
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Haalt het attribuut op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| attribuut | java.lang.String | Het attribuut. |

**Returns:**
java.lang.String - Retourneert het attribuut voor de opgegeven attribuutnaam.
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


Haalt namespace-URI op op basis van een specifiek prefix. Prefix mag beginnen zonder xmlns.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | java.lang.String | De prefix. |

**Returns:**
java.lang.String - Retourneert een pakketschema-URI.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converteert xmp‑waarde naar de xml‑representatie.

**Returns:**
java.lang.String - Retourneert XMP-waarde geconverteerd naar XML-tekenreeks.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor dit exemplaar.

**Returns:**
int - Een hashcode voor deze instantie, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel.
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Geeft aan of het huidige object gelijk is aan een ander object van hetzelfde type.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Een object om te vergelijken met dit object. |

**Returns:**
boolean - true als het huidige object gelijk is aan de  other  parameter; anders, false.
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


Voegt namespace-URI toe via prefix. Prefix mag beginnen zonder xmlns.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | java.lang.String | De prefix. |
| namespaceUri | java.lang.String | Pakket‑schema‑uri. |

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

