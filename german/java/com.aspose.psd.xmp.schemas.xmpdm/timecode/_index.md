---
title: "Timecode"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt den Timecode-Wert im Video dar."
type: docs
weight: 15
url: /de/java/com.aspose.psd.xmp.schemas.xmpdm/timecode/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class Timecode extends XmpTypeBase implements System.IEquatable<Timecode>
```

Stellt den Timecode-Wert im Video dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Timecode(TimeFormat format, String timeValue)](#Timecode-com.aspose.psd.xmp.schemas.xmpdm.TimeFormat-java.lang.String-) | Initialisiert eine neue Instanz der  Timecode  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene  System.Object  gleich dieser Instanz ist. |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | Liest oder setzt das Format, das im  TimeValue  verwendet wird. |
| [getTimeValue()](#getTimeValue--) | Liest oder setzt den Zeitwert im angegebenen Format. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gibt den im String enthaltenen Wert im XMP-Format zurück. |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück. |
| [isEquals(Timecode other)](#isEquals-com.aspose.psd.xmp.schemas.xmpdm.Timecode-) | Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFormat(TimeFormat value)](#setFormat-com.aspose.psd.xmp.schemas.xmpdm.TimeFormat-) | Liest oder setzt das Format, das im  TimeValue  verwendet wird. |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | Liest oder setzt den Zeitwert im angegebenen Format. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Timecode(TimeFormat format, String timeValue) {#Timecode-com.aspose.psd.xmp.schemas.xmpdm.TimeFormat-java.lang.String-}
```
public Timecode(TimeFormat format, String timeValue)
```


Initialisiert eine neue Instanz der  Timecode  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | [TimeFormat](../../com.aspose.psd.xmp.schemas.xmpdm/timeformat) | Das Zeitformat. |
| timeValue | java.lang.String | Der Zeitwert. |

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
### getFormat() {#getFormat--}
```
public TimeFormat getFormat()
```


Liest oder setzt das Format, das im  TimeValue  verwendet wird.

Wert: Das im  TimeValue  verwendete Format.

**Returns:**
[TimeFormat](../../com.aspose.psd.xmp.schemas.xmpdm/timeformat)
### getTimeValue() {#getTimeValue--}
```
public String getTimeValue()
```


Liest oder setzt den Zeitwert im angegebenen Format.

Wert: Der Zeitwert im angegebenen Format.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gibt den im String enthaltenen Wert im XMP-Format zurück.

**Returns:**
java.lang.String - Gibt den enthaltenen Zeichenkettenwert im XMP-Format zurück.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück.

**Returns:**
int - Ein Hashcode für diese Instanz, geeignet für die Verwendung in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
### isEquals(Timecode other) {#isEquals-com.aspose.psd.xmp.schemas.xmpdm.Timecode-}
```
public boolean isEquals(Timecode other)
```


Gibt an, ob das aktuelle Objekt einem anderen Objekt desselben Typs gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [Timecode](../../com.aspose.psd.xmp.schemas.xmpdm/timecode) | Ein Objekt zum Vergleich mit diesem Objekt. |

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




### setFormat(TimeFormat value) {#setFormat-com.aspose.psd.xmp.schemas.xmpdm.TimeFormat-}
```
public void setFormat(TimeFormat value)
```


Liest oder setzt das Format, das im  TimeValue  verwendet wird.

Wert: Das im  TimeValue  verwendete Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TimeFormat](../../com.aspose.psd.xmp.schemas.xmpdm/timeformat) |  |

### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public void setTimeValue(String value)
```


Liest oder setzt den Zeitwert im angegebenen Format.

Wert: Der Zeitwert im angegebenen Format.

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

