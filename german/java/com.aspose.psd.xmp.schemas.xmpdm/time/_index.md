---
title: "Time"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Darstellung eines Zeitwerts in Sekunden."
type: docs
weight: 13
url: /de/java/com.aspose.psd.xmp.schemas.xmpdm/time/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Darstellung eines Zeitwerts in Sekunden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.psd.xmp.types.derived.Rational-int-) | Initialisiert eine neue Instanz der  Time  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getScale()](#getScale--) | Liest oder setzt die Skalierung für den Zeitwert. |
| [getValue()](#getValue--) | Liest oder setzt den Zeitwert in der angegebenen Skalierung. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Liest den enthaltenen Zeichenkettenwert im XMP-Format. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setScale(Rational value)](#setScale-com.aspose.psd.xmp.types.derived.Rational-) | Liest oder setzt die Skalierung für den Zeitwert. |
| [setValue(int value)](#setValue-int-) | Liest oder setzt den Zeitwert in der angegebenen Skalierung. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Time(Rational scale, int value) {#Time-com.aspose.psd.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Initialisiert eine neue Instanz der  Time  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.psd.xmp.types.derived/rational) | Die Skalierung. |
| Wert | int | Der Wert. |

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
### getScale() {#getScale--}
```
public Rational getScale()
```


Liest oder setzt die Skalierung für den Zeitwert.

Für NTSC verwenden Sie 1001/30000 oder die weniger genaue 100/2997. Für PAL verwenden Sie 1/25. Wert: Die Skalierung für den Zeitwert.

**Returns:**
[Rational](../../com.aspose.psd.xmp.types.derived/rational)
### getValue() {#getValue--}
```
public int getValue()
```


Liest oder setzt den Zeitwert in der angegebenen Skalierung.

Wert: Der Zeitwert in der angegebenen Skalierung.

**Returns:**
int
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Liest den enthaltenen Zeichenkettenwert im XMP-Format.

**Returns:**
java.lang.String - Gibt den enthaltenen Zeichenkettenwert im XMP-Format zurück.
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


Liest oder setzt die Skalierung für den Zeitwert.

Für NTSC verwenden Sie 1001/30000 oder die weniger genaue 100/2997. Für PAL verwenden Sie 1/25. Wert: Die Skalierung für den Zeitwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rational](../../com.aspose.psd.xmp.types.derived/rational) |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Liest oder setzt den Zeitwert in der angegebenen Skalierung.

Wert: Der Zeitwert in der angegebenen Skalierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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

