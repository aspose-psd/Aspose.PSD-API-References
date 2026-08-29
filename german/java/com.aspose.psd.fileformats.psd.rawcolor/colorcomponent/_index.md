---
title: "ColorComponent"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Farbkomponente ist eine Abstraktion über Kanalwert und Kanalwert."
type: docs
weight: 10
url: /de/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

Color component ist eine Abstraktion über Channel Value und Channel Value. Jede Farbe besteht aus einem Array von ColorComponent
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | Initialisiert eine neue Instanz der [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Liefert die Bit-Tiefe von Color Component/Channel |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Liefert die Beschreibung von Color Component |
| [getFullName()](#getFullName--) | Liefert den vollständigen Namen des color component mit Name und durch Leerzeichen getrennten Beschreibung |
| [getName()](#getName--) | Liefert den Namen des color component. |
| [getPermittedFullNames()](#getPermittedFullNames--) | Liefert die zulässigen vollständigen Namen. |
| [getValue()](#getValue--) | Liest oder setzt den Wert. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | Liest oder setzt den Wert. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


Initialisiert eine neue Instanz der [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) Klasse. Bitte prüfen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| BitTiefe | byte | Die Bit-Tiefe. |
| fullName | java.lang.String | Der vollständige Name. |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Liefert die Bit-Tiefe von Color Component/Channel

Wert: Die Bit-Tiefe.

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Liefert die Beschreibung von Color Component

Value: Die Beschreibung.

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


Liefert den vollständigen Namen des color component mit Name und durch Leerzeichen getrennten Beschreibung

Wert: Der vollständige Name.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


Liefert den Namen des color component.

Wert: Der Name.

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


Liefert die zulässigen vollständigen Namen.

Wert: Die zulässigen vollständigen Namen.

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


Liefert oder setzt den Wert. Bitte beachten Sie, dass Sie, wenn Sie versuchen, einen Wert zu setzen, der größer ist als im aktuellen Bit-Tiefe möglich gespeichert werden kann, eine Ausnahme erhalten.

Wert: Der Wert.

**Returns:**
long
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




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


Liefert oder setzt den Wert. Bitte beachten Sie, dass Sie, wenn Sie versuchen, einen Wert zu setzen, der größer ist als im aktuellen Bit-Tiefe möglich gespeichert werden kann, eine Ausnahme erhalten.

Wert: Der Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

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

