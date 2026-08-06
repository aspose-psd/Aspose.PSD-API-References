---
title: "TiffExifIfd"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La classe de répertoire de fichiers image TIFF Exif."
type: docs
weight: 11
url: /fr/java/com.aspose.psd.fileformats.tiff/tiffexififd/
---

**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

La classe de répertoire de fichiers image TIFF Exif.

Encapsule un pointeur vers l'Exif IFD. Interoperability, l'Exif IFD a la même structure que celle de l'IFD spécifié dans le TIFF. Ordinairement, cependant, il ne contient pas de données d'image comme dans le cas du TIFF. Voir http://www.exiv2.org/tags.html et http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html pour plus de détails.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Initialise une nouvelle instance de la classe  TiffExifIfd . |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Initialise une nouvelle instance de la classe  TiffExifIfd . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOffset()](#getOffset--) | Obtient ou définit le pointeur vers EXIF IFD. |
| [hasValue()](#hasValue--) | Obtient une valeur indiquant si cette instance possède une valeur. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffset(long value)](#setOffset-long-) | Obtient ou définit le pointeur vers EXIF IFD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Initialise une nouvelle instance de la classe  TiffExifIfd .

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Initialise une nouvelle instance de la classe  TiffExifIfd .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | ifdOffset | long | Un pointeur vers l'IFD Exif. |

Interoperability, l'Exif IFD a la même structure que celle de l'IFD spécifié dans le TIFF. Ordinairement, cependant, il ne contient pas de données d'image comme dans le cas du TIFF. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Obtient ou définit le pointeur vers EXIF IFD.

**Returns:**
long - Le pointeur vers l' EXIF IFD.
### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Obtient une valeur indiquant si cette instance possède une valeur.

**Returns:**
booléen -  true  si cette instance possède une valeur; sinon,  false .
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


Obtient ou définit le pointeur vers EXIF IFD.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | Le pointeur vers l' EXIF IFD. |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

