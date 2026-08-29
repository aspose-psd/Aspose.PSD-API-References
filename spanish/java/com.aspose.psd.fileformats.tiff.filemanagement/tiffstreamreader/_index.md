---
title: "TiffStreamReader"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El flujo TIFF para manejar el formato de archivo TIFF de little endian."
type: docs
weight: 10
url: /es/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

El flujo TIFF para manejar el formato de archivo TIFF de little endian.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Inicializa una nueva instancia de la clase TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Inicializa una nueva instancia de la clase TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Inicializa una nueva instancia de la clase TiffStreamReader. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | Inicializa una nueva instancia de la clase TiffStreamReader. |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Obtiene la longitud del lector. |
| [getThrowExceptions()](#getThrowExceptions--) | Obtiene o establece un valor que indica si se lanzan excepciones al procesar datos incorrectos (lectura o escritura en el flujo). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Lee una matriz de valores byte del flujo. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Lee una matriz de valores byte sin signo del flujo. |
| [readDouble(long position)](#readDouble-long-) | Lee un único valor double del flujo. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Lee una matriz de valores double del flujo. |
| [readFloat(long position)](#readFloat-long-) | Lee un único valor float del flujo. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Lee una matriz de valores float del flujo. |
| [readRational(long position)](#readRational-long-) | Lee un único valor de número racional del flujo. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Lee una matriz de valores racionales del flujo. |
| [readSByte(long position)](#readSByte-long-) | Lee datos byte con signo del flujo. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Lee una matriz de valores byte con signo del flujo. |
| [readSLong(long position)](#readSLong-long-) | Lee un valor entero con signo del flujo. |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | Lee una matriz de valores enteros con signo del flujo. |
| [readSRational(long position)](#readSRational-long-) | Lee un único valor de número racional con signo del flujo. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Lee una matriz de valores racionales con signo del flujo. |
| [readSShort(long position)](#readSShort-long-) | Lee un valor short con signo del flujo. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Lee una matriz de valores short con signo del flujo. |
| [readString_internalized(long position)](#readString-internalized-long-) | Lee la cadena del flujo. |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | Lee la cadena del flujo. |
| [readULong(long position)](#readULong-long-) | Lee un valor entero sin signo del flujo. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Lee una matriz de valores enteros sin signo del flujo. |
| [readUShort(long position)](#readUShort-long-) | Lee un valor short sin signo del flujo. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Lee una matriz de valores enteros sin signo del flujo. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Obtiene o establece un valor que indica si se lanzan excepciones al procesar datos incorrectos (lectura o escritura en el flujo). |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Convierte los datos subyacentes al contenedor de flujo. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Inicializa una nueva instancia de la clase TiffStreamReader.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Los datos de la matriz de bytes. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Inicializa una nueva instancia de la clase TiffStreamReader.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Los datos de la matriz de bytes. |
| startIndex | int | El índice de inicio en los datos. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Inicializa una nueva instancia de la clase TiffStreamReader.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Los datos de la matriz de bytes. |
| startIndex | int | El índice de inicio en los datos. |
| dataLength | int | Longitud de los datos. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Inicializa una nueva instancia de la clase TiffStreamReader.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |

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
### getLength() {#getLength--}
```
public long getLength()
```


Obtiene la longitud del lector.

Valor: La longitud del lector.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Obtiene o establece un valor que indica si se lanzan excepciones al procesar datos incorrectos (lectura o escritura en el flujo).

Valor:  true  si se lanzan excepciones al procesar datos incorrectos; de lo contrario, las condiciones de error se ignoran silenciosamente.

**Returns:**
boolean
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




### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


Lee una matriz de valores byte del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | byte[] | La matriz a rellenar. |
| arrayIndex | int | El índice de la matriz donde comenzar a colocar valores. |
| position | long | La posición del flujo desde la cual leer. |
| count | long | El recuento de elementos a leer. |

**Returns:**
long - La matriz de valores byte.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Lee una matriz de valores byte sin signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
byte[] - La matriz de valores byte sin signo.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Lee un único valor double del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |

**Returns:**
double - El valor doble único.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Lee una matriz de valores double del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
double[] - La matriz de valores dobles.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Lee un único valor float del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |

**Returns:**
float - El valor float único.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Lee una matriz de valores float del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
float[] - La matriz de valores float.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Lee un único valor de número racional del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Lee una matriz de valores racionales del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - La matriz de valores racionales.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Lee datos byte con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |

**Returns:**
byte - El valor byte con signo.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Lee una matriz de valores byte con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
byte[] - La matriz de valores byte con signo.
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


Lee un valor entero con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |

**Returns:**
int - Un valor entero con signo.
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


Lee una matriz de valores enteros con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
int[] - La matriz de valores enteros con signo.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Lee un único valor de número racional con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Lee una matriz de valores racionales con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - La matriz de valores racionales con signo.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Lee un valor short con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |

**Returns:**
short - Un valor short con signo.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Lee una matriz de valores short con signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
short[] - La matriz de valores short con signo.
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


Lee la cadena del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición. |

**Returns:**
java.lang.String - La cadena.
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


Lee la cadena del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición. |
| longitud | long | La longitud. |

**Returns:**
java.lang.String - La cadena.
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


Lee un valor entero sin signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |

**Returns:**
long - Un valor entero sin signo.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


Lee una matriz de valores enteros sin signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
long[] - La matriz de valores enteros sin signo.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Lee un valor short sin signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |

**Returns:**
int - Un valor short sin signo.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Lee una matriz de valores enteros sin signo del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual leer. |
| count | long | El recuento de elementos. |

**Returns:**
int[] - La matriz de valores enteros sin signo.
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Obtiene o establece un valor que indica si se lanzan excepciones al procesar datos incorrectos (lectura o escritura en el flujo).

Valor:  true  si se lanzan excepciones al procesar datos incorrectos; de lo contrario, las condiciones de error se ignoran silenciosamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Convierte los datos subyacentes al contenedor de flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| posicionInicial | long | La posición inicial desde la que comenzar la conversión. |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  with converted data.
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

