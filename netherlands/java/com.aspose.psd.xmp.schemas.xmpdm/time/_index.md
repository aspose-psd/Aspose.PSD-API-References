---
title: "Time"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Representatie van een tijdwaarde in seconden."
type: docs
weight: 13
url: /nl/java/com.aspose.psd.xmp.schemas.xmpdm/time/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Representatie van een tijdwaarde in seconden.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.psd.xmp.types.derived.Rational-int-) | Initialiseert een nieuw exemplaar van de  Time  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getScale()](#getScale--) | Haalt op of stelt de schaal in voor de tijdwaarde. |
| [getValue()](#getValue--) | Haalt op of stelt de tijdwaarde in de opgegeven schaal in. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Haalt de tekenreeksinhoud op in XMP-indeling. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setScale(Rational value)](#setScale-com.aspose.psd.xmp.types.derived.Rational-) | Haalt op of stelt de schaal in voor de tijdwaarde. |
| [setValue(int value)](#setValue-int-) | Haalt op of stelt de tijdwaarde in de opgegeven schaal in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Time(Rational scale, int value) {#Time-com.aspose.psd.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Initialiseert een nieuw exemplaar van de  Time  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.psd.xmp.types.derived/rational) | De schaal. |
| waarde | int | De waarde. |

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
### getScale() {#getScale--}
```
public Rational getScale()
```


Haalt op of stelt de schaal in voor de tijdwaarde.

Voor NTSC, gebruik 1001/30000, of de minder nauwkeurige 100/2997. Voor PAL, gebruik 1/25. Waarde: De schaal voor de tijdwaarde.

**Returns:**
[Rational](../../com.aspose.psd.xmp.types.derived/rational)
### getValue() {#getValue--}
```
public int getValue()
```


Haalt op of stelt de tijdwaarde in de opgegeven schaal in.

Waarde: De tijdwaarde in de opgegeven schaal.

**Returns:**
int
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Haalt de tekenreeksinhoud op in XMP-indeling.

**Returns:**
java.lang.String - Retourneert de tekenreeksinhoud in XMP-indeling.
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




### setScale(Rational value) {#setScale-com.aspose.psd.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Haalt op of stelt de schaal in voor de tijdwaarde.

Voor NTSC, gebruik 1001/30000, of de minder nauwkeurige 100/2997. Voor PAL, gebruik 1/25. Waarde: De schaal voor de tijdwaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Rational](../../com.aspose.psd.xmp.types.derived/rational) |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Haalt op of stelt de tijdwaarde in de opgegeven schaal in.

Waarde: De tijdwaarde in de opgegeven schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

