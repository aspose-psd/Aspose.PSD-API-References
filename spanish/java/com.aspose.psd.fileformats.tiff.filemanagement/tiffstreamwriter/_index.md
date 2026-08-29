---
title: "TiffStreamWriter"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Escritor de flujo TIFF."
type: docs
weight: 11
url: /es/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter implements ISynchronizable
```

Escritor de flujo TIFF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.psd.StreamContainer-) | Inicializa una nueva instancia de la clase  TiffStreamWriter  . |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPosition()](#getPosition--) | Obtiene o establece la posición del flujo. |
| [getSyncRoot()](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPosition(long value)](#setPosition-long-) | Obtiene o establece la posición del flujo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] data)](#write-byte---) | Escribe los datos especificados. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Escribe los datos especificados. |
| [writeDouble(double data)](#writeDouble-double-) | Escribe un único valor double al flujo. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Escribe una matriz de valores double al flujo. |
| [writeFloat(float data)](#writeFloat-float-) | Escribe un único valor float al flujo. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Escribe una matriz de valores float al flujo. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-) | Escribe un único valor de número racional al flujo. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---) | Escribe una matriz de valores racionales sin signo al flujo. |
| [writeSByte(byte data)](#writeSByte-byte-) | Escribe un único valor de byte con signo al flujo. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Escribe una matriz de valores de byte con signo al flujo. |
| [writeSLongArray(int[] data)](#writeSLongArray-int---) | Escribe una matriz de valores enteros al flujo. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-) | Escribe un único valor de número racional con signo en el flujo. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---) | Escribe una matriz de valores racionales con signo en el flujo. |
| [writeSShort(short data)](#writeSShort-short-) | Escribe un único valor corto en el flujo. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Escribe una matriz de valores cortos en el flujo. |
| [writeSlong(int data)](#writeSlong-int-) | Escribe un único valor entero en el flujo. |
| [writeUByte(byte data)](#writeUByte-byte-) | Escribe un único valor de byte en el flujo. |
| [writeULong(long data)](#writeULong-long-) | Escribe un único valor entero sin signo en el flujo. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Escribe una matriz de valores enteros sin signo en el flujo. |
| [writeUShort(int data)](#writeUShort-int-) | Escribe un único valor corto sin signo en el flujo. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Escribe una matriz de valores cortos sin signo en el flujo. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.psd.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


Inicializa una nueva instancia de la clase  TiffStreamWriter  .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El escritor de flujo. |

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
### getPosition() {#getPosition--}
```
public long getPosition()
```


Obtiene o establece la posición del flujo.

Valor: La posición del flujo.

**Returns:**
long
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado.

Valor: El objeto que puede usarse para sincronizar el acceso al recurso sincronizado.

**Returns:**
java.lang.Object
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




### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Obtiene o establece la posición del flujo.

Valor: La posición del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

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

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Escribe los datos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Los datos a escribir. |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Escribe los datos especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Los datos a escribir. |
| offset | int | El desplazamiento de los datos. |
| dataLength | int | Longitud de los datos a escribir. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Escribe un único valor double al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | double | El valor a escribir. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Escribe una matriz de valores double al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | double[] | La matriz a escribir. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Escribe un único valor float al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | float | El valor a escribir. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Escribe una matriz de valores float al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | float[] | La matriz a escribir. |

### writeRational(TiffRational data) {#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Escribe un único valor de número racional al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | El valor a escribir. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Escribe una matriz de valores racionales sin signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | La matriz a escribir. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Escribe un único valor de byte con signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte | El valor a escribir. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Escribe una matriz de valores de byte con signo al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | La matriz a escribir. |

### writeSLongArray(int[] data) {#writeSLongArray-int---}
```
public void writeSLongArray(int[] data)
```


Escribe una matriz de valores enteros al flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | int[] | La matriz a escribir. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Escribe un único valor de número racional con signo en el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) | El valor a escribir. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Escribe una matriz de valores racionales con signo en el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffsrational) | La matriz a escribir. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Escribe un único valor corto en el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | short | El valor a escribir. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Escribe una matriz de valores cortos en el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | short[] | La matriz a escribir. |

### writeSlong(int data) {#writeSlong-int-}
```
public void writeSlong(int data)
```


Escribe un único valor entero en el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | int | El valor a escribir. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Escribe un único valor de byte en el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte | El valor a escribir. |

### writeULong(long data) {#writeULong-long-}
```
public void writeULong(long data)
```


Escribe un único valor entero sin signo en el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | long | El valor a escribir. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public void writeULongArray(long[] data)
```


Escribe una matriz de valores enteros sin signo en el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | long[] | La matriz a escribir. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Escribe un único valor corto sin signo en el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | int | El valor a escribir. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Escribe una matriz de valores cortos sin signo en el flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | int[] | La matriz a escribir. |

