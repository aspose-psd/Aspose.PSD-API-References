---
title: "XmpMeta"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt xmpmeta dar."
type: docs
weight: 17
url: /de/java/com.aspose.psd.xmp/xmpmeta/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Stellt xmpmeta dar. Optional. Der Zweck dieses Elements ist es, XMP-Metadaten innerhalb allgemeinen XML-Textes zu identifizieren, der andere nicht-XMP-Verwendungen von RDF enthalten könnte.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Initialisiert eine neue Instanz der  XmpMeta  Klasse. |
| [XmpMeta()](#XmpMeta--) | Initialisiert eine neue Instanz der  XmpMeta  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Fügt das Attribut hinzu. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Weist das angegebene XMP-Element dem aktuellen zu. |
| [clearAttributes()](#clearAttributes--) | Entfernt alle Attribute. |
| [deepClone_internalized()](#deepClone-internalized--) | Klont diese Instanz. |
| [equals(Object other)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene  System.Object  gleich dieser Instanz ist. |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Liest oder setzt die Adobe Xmp Toolkit-Version. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Liest das Attribut. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.psd.xmp.XmpMeta-) | Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Liest oder setzt die Adobe Xmp Toolkit-Version. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Initialisiert eine neue Instanz der  XmpMeta  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Adobe XMP Toolkit-Version. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Initialisiert eine neue Instanz der  XmpMeta  Klasse.

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
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Bestimmt, ob das angegebene  System.Object  gleich dieser Instanz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Andere | java.lang.Object | Das  System.Object  zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  true  wenn das angegebene  System.Object  dieser Instanz gleich ist; andernfalls  false .
### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Liest oder setzt die Adobe Xmp Toolkit-Version.

**Returns:**
java.lang.String
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
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns:**
java.lang.String - Gibt den XMP-Wert zurück, der in die XML-Darstellung konvertiert wurde.
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
### isEquals(XmpMeta other) {#isEquals-com.aspose.psd.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Ein Objekt zum Vergleich mit diesem Objekt. |

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




### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Liest oder setzt die Adobe Xmp Toolkit-Version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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

