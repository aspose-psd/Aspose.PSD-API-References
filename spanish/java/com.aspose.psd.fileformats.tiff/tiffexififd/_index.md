---
title: "TiffExifIfd"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Clase del directorio de archivo de imagen Exif TIFF."
type: docs
weight: 11
url: /es/java/com.aspose.psd.fileformats.tiff/tiffexififd/
---

**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

Clase del directorio de archivo de imagen Exif TIFF.

Encapsula un puntero al Exif IFD. Interoperabilidad, Exif IFD tiene la misma estructura que el IFD especificado en TIFF. Sin embargo, ordinariamente, no contiene datos de imagen como en el caso de TIFF. Consulte http://www.exiv2.org/tags.html y http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html para más detalles.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Inicializa una nueva instancia de la  TiffExifIfd  clase. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Inicializa una nueva instancia de la  TiffExifIfd  clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOffset()](#getOffset--) | Obtiene o establece el puntero al EXIF IFD. |
| [hasValue()](#hasValue--) | Obtiene un valor que indica si esta instancia tiene valor. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffset(long value)](#setOffset-long-) | Obtiene o establece el puntero al EXIF IFD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Inicializa una nueva instancia de la  TiffExifIfd  clase.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Inicializa una nueva instancia de la  TiffExifIfd  clase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | ifdOffset | long | Un puntero al IFD de Exif. |

Interoperabilidad, Exif IFD tiene la misma estructura que el IFD especificado en TIFF. Sin embargo, ordinariamente, no contiene datos de imagen como en el caso de TIFF. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Obtiene o establece el puntero al EXIF IFD.

**Returns:**
long - El puntero al EXIF IFD.
### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Obtiene un valor que indica si esta instancia tiene valor.

**Returns:**
boolean -  true  si esta instancia tiene valor; de lo contrario,  false .
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


Obtiene o establece el puntero al EXIF IFD.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | El puntero a EXIF IFD. |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

