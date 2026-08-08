---
title: "XmpDate"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt datum in XMP-pakket voor."
type: docs
weight: 11
url: /nl/java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Stelt datum in XMP-pakket voor.

Een datum‑tijdwaarde wordt weergegeven met behulp van een deelset van de formaten zoals gedefinieerd in Datum‑ en Tijdformaten: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Initialiseert een nieuw exemplaar van de  XmpDate  klasse. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Initialiseert een nieuw exemplaar van de  XmpDate  klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | De ISO 8601 (round‑trip) opmaakreeks. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | Haalt de opmaakstring op voor de huidige waarde. |
| [getValue()](#getValue--) | Haalt de datumwaarde op of stelt deze in. |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | Retourneert de tekenreeks die de waarde bevat in XMP-indeling. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | Haalt de datumwaarde op of stelt deze in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Initialiseert een nieuw exemplaar van de  XmpDate  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dateTime | java.util.Date | Een datum‑tijdwaarde die wordt weergegeven met behulp van een subset van ISO RFC 8601-opmaak. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Initialiseert een nieuw exemplaar van de  XmpDate  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dateString | java.lang.String | De tekenreeksrepresentatie van de datum. |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


De ISO 8601 (round‑trip) opmaakreeks.

Bekijk meer: https://en.wikipedia.org/wiki/ISO\\_8601.

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
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
### getFormat() {#getFormat--}
```
public String getFormat()
```


Haalt de opmaakstring op voor de huidige waarde.

Waarde: De opmaakstring voor de huidige waarde.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


Haalt de datumwaarde op of stelt deze in.

Waarde: De datumwaarde.

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


Retourneert de tekenreeks die de waarde bevat in XMP-indeling.

**Returns:**
java.lang.String - Retourneert de tekenreeks die de waarde bevat in XMP-indeling.
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


Haalt de datumwaarde op of stelt deze in.

Waarde: De datumwaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Date |  |

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

