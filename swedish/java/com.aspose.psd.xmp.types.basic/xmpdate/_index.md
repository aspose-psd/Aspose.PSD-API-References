---
title: "XmpDate"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar datum i XMP-paket."
type: docs
weight: 11
url: /sv/java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Representerar datum i XMP-paket.

Ett datum‑tid‑värde representeras med ett delmängd av formaten enligt definierade datum‑ och tidsformat: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Initierar en ny instans av klassen  XmpDate  . |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Initierar en ny instans av klassen  XmpDate  . |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | ISO 8601‑formatsträngen (rundresa). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | Hämtar formatsträngen för det aktuella värdet. |
| [getValue()](#getValue--) | Hämtar eller anger datumvärdet. |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returnerar strängens innehållsvärde i XMP-format. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | Hämtar eller anger datumvärdet. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Initierar en ny instans av klassen  XmpDate  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dateTime | java.util.Date | Ett datum‑tidsvärde som representeras med en delmängd av ISO RFC 8601‑formatering. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Initierar en ny instans av klassen  XmpDate  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dateString | java.lang.String | Strängrepresentationen av datum. |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


ISO 8601‑formatsträngen (rundresa).

Se mer: https://en.wikipedia.org/wiki/ISO\_8601.

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
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
### getFormat() {#getFormat--}
```
public String getFormat()
```


Hämtar formatsträngen för det aktuella värdet.

Värde: Formatsträngen för aktuellt värde.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


Hämtar eller anger datumvärdet.

Värde: Datumvärdet.

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


Returnerar strängens innehållsvärde i XMP-format.

**Returns:**
java.lang.String - Returnerar strängens innehållsvärde i XMP-format.
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


Hämtar eller anger datumvärdet.

Värde: Datumvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

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

