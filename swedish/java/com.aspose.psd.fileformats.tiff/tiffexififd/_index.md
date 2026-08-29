---
title: "TiffExifIfd"
second_title: "Aspose.PSD för Java API-referens"
description: "Klassen för TIFF Exif-bildfilkatalog."
type: docs
weight: 11
url: /sv/java/com.aspose.psd.fileformats.tiff/tiffexififd/
---

**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

Klassen för TIFF Exif-bildfilkatalog.

Inkapslar en pekare till Exif IFD. Interoperabilitet, Exif IFD har samma struktur som IFD specificerad i TIFF. Vanligtvis innehåller den dock inte bilddata som i fallet med TIFF. Se http://www.exiv2.org/tags.html och http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html för mer detaljer.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Initierar en ny instans av klassen  TiffExifIfd  . |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Initierar en ny instans av klassen  TiffExifIfd  . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOffset()](#getOffset--) | Hämtar eller anger pekaren till EXIF IFD. |
| [hasValue()](#hasValue--) | Hämtar ett värde som indikerar om den här instansen har ett värde. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffset(long value)](#setOffset-long-) | Hämtar eller anger pekaren till EXIF IFD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Initierar en ny instans av klassen  TiffExifIfd  .

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Initierar en ny instans av klassen  TiffExifIfd  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ifdOffset | long | En pekare till Exif IFD. |

Interoperabilitet, Exif IFD har samma struktur som IFD specificerad i TIFF. Vanligtvis innehåller den dock inte bilddata som i fallet med TIFF. |

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
### getOffset() {#getOffset--}
```
public long getOffset()
```


Hämtar eller anger pekaren till EXIF IFD.

**Returns:**
long - Pekaren till EXIF IFD.
### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Hämtar ett värde som indikerar om den här instansen har ett värde.

**Returns:**
boolean -  true  om den här instansen har ett värde; annars,  false .
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


Hämtar eller anger pekaren till EXIF IFD.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Pekaren till EXIF IFD. |

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

