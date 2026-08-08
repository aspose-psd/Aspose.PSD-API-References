---
title: "XmpHeaderPi"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar XMP-headerprocessinstruktion."
type: docs
weight: 16
url: /sv/java/com.aspose.psd.xmp/xmpheaderpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Representerar XMP-headerprocessinstruktion.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Initierar en ny instans av klassen  XmpHeaderPi  . |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Initierar en ny instans av klassen  XmpHeaderPi  . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Klonar den här instansen. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna  System.Object  är lika med den här instansen. |
| [getClass()](#getClass--) |  |
| [getGuid()](#getGuid--) | Representerar Header Guid. |
| [getXmlValue()](#getXmlValue--) | Konverterar XMP‑värdet till XML‑representationen. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för den här instansen. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.psd.xmp.XmpHeaderPi-) | Anger om det aktuella objektet är lika med ett annat objekt av samma typ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(String value)](#setGuid-java.lang.String-) | Representerar Header Guid. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Initierar en ny instans av klassen  XmpHeaderPi  .

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Initierar en ny instans av klassen  XmpHeaderPi  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| guid | java.lang.String | Den unika identifieraren. |

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpHeaderPi deepClone_internalized()
```


Klonar den här instansen.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna  System.Object  är lika med den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det  System.Object  att jämföra med den här instansen. |

**Returns:**
boolean -  true  om det angivna  System.Object  är lika med den här instansen; annars  false .
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


Representerar Header Guid.

Texten i header PI innehåller ett GUID, vilket gör det osannolikt att den dyker upp av misstag i dataströmmen.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Konverterar XMP‑värdet till XML‑representationen.

**Returns:**
java.lang.String - Returnerar XMP-värdet konverterat till XML-representationen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för den här instansen.

**Returns:**
int - En hashkod för den här instansen, lämplig för användning i hash‑algoritmer och datastrukturer som en hashtabell.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.psd.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Anger om det aktuella objektet är lika med ett annat objekt av samma typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Ett objekt att jämföra med detta objekt. |

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




### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Representerar Header Guid.

Texten i header PI innehåller ett GUID, vilket gör det osannolikt att den dyker upp av misstag i dataströmmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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

