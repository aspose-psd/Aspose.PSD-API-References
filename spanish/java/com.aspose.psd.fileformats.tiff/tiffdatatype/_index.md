---
title: "TiffDataType"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El tipo de datos TIFF."
type: docs
weight: 10
url: /es/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

El tipo de datos TIFF.
## Métodos

| Método | Descripción |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | Compara la instancia actual con otro objeto del mismo tipo y devuelve un entero que indica si la instancia actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto. |
| [deepClone()](#deepClone--) | Realiza una clonación profunda de esta instancia. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | Obtiene el tamaño adicional de los datos en bytes (en caso de que los 12 bytes no sean suficientes para contener los datos de la etiqueta). |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Obtiene la cantidad de elementos. |
| [getDataSize()](#getDataSize--) | Obtiene el tamaño adicional de los datos en bytes (en caso de que los 12 bytes no sean suficientes para contener los datos de la etiqueta). |
| [getId()](#getId--) | Obtiene la representación entera del id de la etiqueta. |
| [getTagId()](#getTagId--) | Obtiene el id de la etiqueta. |
| [getTagType()](#getTagType--) | Obtiene el tipo de la etiqueta. |
| [getValue()](#getValue--) | Obtiene el valor que contiene este tipo de datos. |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | Obtiene un valor que indica si la etiqueta es privada. |
| [isValid()](#isValid--) | Obtiene un valor que indica si los datos de la etiqueta son válidos. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Lee los datos de la etiqueta. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Establece el valor que contiene este tipo de datos. |
| [toString()](#toString--) | Devuelve un  System.String  que representa esta instancia. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | Escribe los datos adicionales de la etiqueta. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Escribe los datos de la etiqueta. |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Compara la instancia actual con otro objeto del mismo tipo y devuelve un entero que indica si la instancia actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Un objeto para comparar con esta instancia. |

**Returns:**
int - Un entero con signo de 32 bits que indica el orden relativo de los objetos que se comparan. El valor de retorno tiene los siguientes significados: Valor Significado Menor que cero Esta instancia es menor que obj. Cero Esta instancia es igual a obj. Mayor que cero Esta instancia es mayor que obj.
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Realiza una clonación profunda de esta instancia.

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


Obtiene el tamaño adicional de los datos en bytes (en caso de que los 12 bytes no sean suficientes para contener los datos de la etiqueta).

**Returns:**
long - El tamaño adicional de los datos en bytes.

Este es el recuento de bytes de datos alineado al límite de palabra.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract long getCount()
```


Obtiene la cantidad de elementos.

**Returns:**
long - La cantidad de elementos.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


Obtiene el tamaño adicional de los datos en bytes (en caso de que los 12 bytes no sean suficientes para contener los datos de la etiqueta).

**Returns:**
long - El tamaño adicional de los datos en bytes.

Este es el recuento exacto de bytes.
### getId() {#getId--}
```
public int getId()
```


Obtiene la representación entera del id de la etiqueta.

**Returns:**
int - La representación entera del id de la etiqueta
### getTagId() {#getTagId--}
```
public int getTagId()
```


Obtiene el id de la etiqueta.

**Returns:**
int - El id de la etiqueta.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Obtiene el tipo de la etiqueta.

**Returns:**
int - El tipo de etiqueta.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Obtiene el valor que contiene este tipo de datos.

**Returns:**
java.lang.Object - El valor.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isPrivate_internalized() {#isPrivate-internalized--}
```
public boolean isPrivate_internalized()
```


Obtiene un valor que indica si la etiqueta es privada. Las etiquetas TIFF privadas son etiquetas con id de etiqueta superior a 32768.

**Returns:**
boolean -  true  si los datos de la etiqueta son válidos; de lo contrario,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Obtiene un valor que indica si los datos de la etiqueta son válidos. La etiqueta válida contiene datos que pueden preservarse. La etiqueta inválida no puede almacenarse.

**Returns:**
boolean -  true  si los datos de la etiqueta son válidos; de lo contrario,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Lee los datos de la etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | La secuencia de datos. |
| position | long | La posición de la etiqueta. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Establece el valor que contiene este tipo de datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object | El valor. |

### toString() {#toString--}
```
public String toString()
```


Devuelve un  System.String  que representa esta instancia.

**Returns:**
java.lang.String - Un  System.String  que representa esta instancia.
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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Escribe los datos adicionales de la etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | La secuencia de datos. |

**Returns:**
long - Los bytes reales escritos.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Escribe los datos de la etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | La secuencia de datos. |
| additionalDataOffset | long | El desplazamiento al que escribir datos adicionales. |

