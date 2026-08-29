---
title: "TiffExifIfd"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La classe della directory file immagine TIFF Exif."
type: docs
weight: 11
url: /it/java/com.aspose.psd.fileformats.tiff/tiffexififd/
---

**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

La classe della directory file immagine TIFF Exif.

Incapsula un puntatore all'Exif IFD. Interoperability, Exif IFD ha la stessa struttura di quella dell'IFD specificato in TIFF. Ordinaramente, tuttavia, non contiene dati immagine come nel caso di TIFF. Vedi http://www.exiv2.org/tags.html e http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html per maggiori dettagli.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Inizializza una nuova istanza della classe  TiffExifIfd . |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Inizializza una nuova istanza della classe  TiffExifIfd . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOffset()](#getOffset--) | Ottiene o imposta il puntatore a EXIF IFD. |
| [hasValue()](#hasValue--) | Restituisce un valore che indica se questa istanza ha un valore. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffset(long value)](#setOffset-long-) | Ottiene o imposta il puntatore a EXIF IFD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Inizializza una nuova istanza della classe  TiffExifIfd .

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Inizializza una nuova istanza della classe  TiffExifIfd .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | ifdOffset | long | Un puntatore all'IFD Exif. |

Interoperability, Exif IFD ha la stessa struttura di quella dell'IFD specificato in TIFF. Ordinaramente, tuttavia, non contiene dati immagine come nel caso di TIFF. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Ottiene o imposta il puntatore a EXIF IFD.

**Returns:**
long - Il puntatore a EXIF IFD.
### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Restituisce un valore che indica se questa istanza ha un valore.

**Returns:**
boolean -  true  se questa istanza ha un valore; altrimenti,  false .
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


Ottiene o imposta il puntatore a EXIF IFD.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | Il puntatore a EXIF IFD. |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

