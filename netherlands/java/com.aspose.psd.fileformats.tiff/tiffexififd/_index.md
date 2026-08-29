---
title: "TiffExifIfd"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De TIFF Exif-afbeeldingsbestandsdirectoryklasse."
type: docs
weight: 11
url: /nl/java/com.aspose.psd.fileformats.tiff/tiffexififd/
---

**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

De TIFF Exif-afbeeldingsbestandsdirectoryklasse.

Omvat een pointer naar de Exif IFD. Interoperabiliteit, Exif IFD heeft dezelfde structuur als die van de IFD gespecificeerd in TIFF. Gewoonlijk bevat het echter geen beeldgegevens zoals in het geval van TIFF. Zie http://www.exiv2.org/tags.html en http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html voor meer details.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Initialiseert een nieuw exemplaar van de  TiffExifIfd  klasse. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Initialiseert een nieuw exemplaar van de  TiffExifIfd  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOffset()](#getOffset--) | Haalt de pointer naar EXIF IFD op of stelt deze in. |
| [hasValue()](#hasValue--) | Haalt een waarde op die aangeeft of dit exemplaar een waarde heeft. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffset(long value)](#setOffset-long-) | Haalt de pointer naar EXIF IFD op of stelt deze in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Initialiseert een nieuw exemplaar van de  TiffExifIfd  klasse.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Initialiseert een nieuw exemplaar van de  TiffExifIfd  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | ifdOffset | long | Een verwijzing naar de Exif IFD. |

Interoperabiliteit, Exif IFD heeft dezelfde structuur als die van de IFD gespecificeerd in TIFF. Gewoonlijk bevat het echter geen beeldgegevens zoals in het geval van TIFF. |

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
### getOffset() {#getOffset--}
```
public long getOffset()
```


Haalt de pointer naar EXIF IFD op of stelt deze in.

**Returns:**
long - De pointer naar EXIF IFD.
### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Haalt een waarde op die aangeeft of dit exemplaar een waarde heeft.

**Returns:**
boolean -  true  als dit exemplaar een waarde heeft; anders,  false .
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


Haalt de pointer naar EXIF IFD op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long | De pointer naar EXIF IFD. |

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

