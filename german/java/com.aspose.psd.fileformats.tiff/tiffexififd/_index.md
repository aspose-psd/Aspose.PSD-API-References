---
title: "TiffExifIfd"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die TIFF-Exif-Bilddateiverzeichnis-Klasse."
type: docs
weight: 11
url: /de/java/com.aspose.psd.fileformats.tiff/tiffexififd/
---

**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

Die TIFF-Exif-Bilddateiverzeichnis-Klasse.

Kapselt einen Zeiger auf das Exif IFD. Interoperabilität, Exif IFD hat dieselbe Struktur wie das im TIFF spezifizierte IFD. gewöhnlich enthält es jedoch keine Bilddaten, wie im Fall von TIFF. Siehe http://www.exiv2.org/tags.html und http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html für weitere Details.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Initialisiert eine neue Instanz der  TiffExifIfd  Klasse. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Initialisiert eine neue Instanz der  TiffExifIfd  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOffset()](#getOffset--) | Liest oder setzt den Zeiger auf EXIF IFD. |
| [hasValue()](#hasValue--) | Gibt einen Wert zurück, der angibt, ob diese Instanz einen Wert hat. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffset(long value)](#setOffset-long-) | Liest oder setzt den Zeiger auf EXIF IFD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Initialisiert eine neue Instanz der  TiffExifIfd  Klasse.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Initialisiert eine neue Instanz der  TiffExifIfd  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | ifdOffset | long | Ein Zeiger auf das Exif‑IFD. |

Interoperabilität, Exif IFD hat dieselbe Struktur wie das im TIFF spezifizierte IFD. gewöhnlich enthält es jedoch keine Bilddaten, wie im Fall von TIFF. |

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
### getOffset() {#getOffset--}
```
public long getOffset()
```


Liest oder setzt den Zeiger auf EXIF IFD.

**Returns:**
long - Der Zeiger auf EXIF IFD.
### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einen Wert hat.

**Returns:**
boolean -  true  wenn diese Instanz einen Wert hat; andernfalls,  false .
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




### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


Liest oder setzt den Zeiger auf EXIF IFD.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Der Zeiger auf EXIF IFD. |

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

