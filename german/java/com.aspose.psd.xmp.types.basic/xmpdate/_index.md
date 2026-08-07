---
title: "XmpDate"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt ein Datum im XMP-Paket dar."
type: docs
weight: 11
url: /de/java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Stellt ein Datum im XMP-Paket dar.

Ein Datum-Uhrzeit-Wert wird unter Verwendung eines Teilsets der Formate dargestellt, wie sie in Datum- und Zeitformaten definiert sind: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Initialisiert eine neue Instanz der  XmpDate  Klasse. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Initialisiert eine neue Instanz der  XmpDate  Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | Der ISO 8601 (Rundreise) Formatstring. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | Liest den Formatstring für den aktuellen Wert. |
| [getValue()](#getValue--) | Liest oder setzt den Datumswert. |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gibt den in XMP-Format enthaltenen Zeichenkettenwert zurück. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | Liest oder setzt den Datumswert. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Initialisiert eine neue Instanz der  XmpDate  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dateTime | java.util.Date | Ein Datum-Uhrzeit-Wert, der unter Verwendung eines Teilsets der ISO RFC 8601-Formatierung dargestellt wird. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Initialisiert eine neue Instanz der  XmpDate  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dateString | java.lang.String | Die Zeichenkettenrepräsentation des Datums. |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


Der ISO 8601 (Rundreise) Formatstring.

Siehe mehr: https://en.wikipedia.org/wiki/ISO\_8601.

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
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
### getFormat() {#getFormat--}
```
public String getFormat()
```


Liest den Formatstring für den aktuellen Wert.

Wert: Die Formatzeichenkette für den aktuellen Wert.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


Liest oder setzt den Datumswert.

Wert: Der Datumswert.

**Returns:**
java.util.Date
### getValue_internalized() {#getValue-internalized--}
```
public System.DateTime getValue_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gibt den in XMP-Format enthaltenen Zeichenkettenwert zurück.

**Returns:**
java.lang.String - Gibt den in XMP-Format enthaltenen Zeichenkettenwert zurück.
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




### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Liest oder setzt den Datumswert.

Wert: Der Datumswert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

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

