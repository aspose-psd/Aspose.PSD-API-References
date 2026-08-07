---
title: "XmpHeaderPi"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt die Verarbeitungsanweisung des XMP-Headers dar."
type: docs
weight: 16
url: /de/java/com.aspose.psd.xmp/xmpheaderpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Stellt die Verarbeitungsanweisung des XMP-Headers dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Initialisiert eine neue Instanz der  XmpHeaderPi  Klasse. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Initialisiert eine neue Instanz der  XmpHeaderPi  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Klont diese Instanz. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene  System.Object  gleich dieser Instanz ist. |
| [getClass()](#getClass--) |  |
| [getGuid()](#getGuid--) | Stellt den Header-Guid dar. |
| [getXmlValue()](#getXmlValue--) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.psd.xmp.XmpHeaderPi-) | Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(String value)](#setGuid-java.lang.String-) | Stellt den Header-Guid dar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Initialisiert eine neue Instanz der  XmpHeaderPi  Klasse.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Initialisiert eine neue Instanz der  XmpHeaderPi  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| guid | java.lang.String | Der eindeutige Bezeichner. |

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpHeaderPi deepClone_internalized()
```


Klont diese Instanz.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene  System.Object  gleich dieser Instanz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das  System.Object  zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  true  wenn das angegebene  System.Object  dieser Instanz gleich ist; andernfalls  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGuid() {#getGuid--}
```
public String getGuid()
```


Stellt den Header-Guid dar.

Der Text der Header-PI enthält einen GUID, wodurch es unwahrscheinlich ist, dass er versehentlich im Datenstrom erscheint.

**Returns:**
java.lang.String
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
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.psd.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Ein Objekt zum Vergleich mit diesem Objekt. |

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




### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Stellt den Header-Guid dar.

Der Text der Header-PI enthält einen GUID, wodurch es unwahrscheinlich ist, dass er versehentlich im Datenstrom erscheint.

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

