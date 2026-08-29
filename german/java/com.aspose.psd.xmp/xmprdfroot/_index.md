---
title: "XmpRdfRoot"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt das rdfRDF-Element dar."
type: docs
weight: 21
url: /de/java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Stellt das rdf:RDF-Element dar. Ein einzelnes XMP-Paket muss mit einem einzigen rdf:RDF-XML-Element serialisiert werden. Der Inhalt des rdf:RDF-Elements darf nur aus null oder mehr rdf:Description-Elementen bestehen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Initialisiert eine neue Instanz der  XmpRdfRoot  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Fügt das Attribut hinzu. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Weist das angegebene XMP-Element dem aktuellen zu. |
| [clearAttributes()](#clearAttributes--) | Entfernt alle Attribute. |
| [deepClone_internalized()](#deepClone-internalized--) | Klont diese Instanz. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene  Object , gleich dieser Instanz ist. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Liest das Attribut. |
| [getClass()](#getClass--) |  |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Liefert den Namespace-URI für ein bestimmtes Präfix. |
| [getXmlValue()](#getXmlValue--) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Fügt einen Namespace-URI anhand eines Präfixes hinzu. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Initialisiert eine neue Instanz der  XmpRdfRoot  Klasse.

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Fügt das Attribut hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Attribut | java.lang.String | Das Attribut. |
| Wert | java.lang.String | Der Wert. |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


Weist das angegebene XMP-Element dem aktuellen zu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Das XMP-Element. |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Entfernt alle Attribute.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


Klont diese Instanz.

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene  Object , gleich dieser Instanz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das  Object  zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  true  wenn das angegebene  Object  dieser Instanz gleich ist; andernfalls,  false .
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Liest das Attribut.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Attribut | java.lang.String | Das Attribut. |

**Returns:**
java.lang.String - Gibt das Attribut für den angegebenen Attributnamen zurück.
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


Liefert den Namespace-URI für ein bestimmtes Präfix. Das Präfix kann ohne xmlns beginnen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | java.lang.String | Das Präfix. |

**Returns:**
java.lang.String - Gibt einen Paket‑Schema‑URI zurück.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns:**
java.lang.String - Gibt den XMP‑Wert als XML‑Zeichenkette zurück.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int - Ein Hashcode für diese Instanz, geeignet für die Verwendung in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Ein Objekt zum Vergleich mit diesem Objekt. |

**Returns:**
boolean - true wenn das aktuelle Objekt dem  other  Parameter gleich ist; andernfalls false.
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


Fügt einen Namespace-URI anhand eines Präfixes hinzu. Das Präfix kann ohne xmlns beginnen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | java.lang.String | Das Präfix. |
| namespaceUri | java.lang.String | Paket-Schema-URI. |

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

