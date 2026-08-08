---
title: "SplitStreamContainer"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa un contenedor de flujo dividido que contiene el flujo y proporciona rutinas de procesamiento de flujo."
type: docs
weight: 102
url: /es/java/com.aspose.psd/splitstreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Representa un contenedor de flujo dividido que contiene el flujo y proporciona rutinas de procesamiento de flujo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Inicializa una nueva instancia de la clase [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Inicializa una nueva instancia de la clase [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-) | Inicializa una nueva instancia de la clase [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
## Campos

| Campo | Descripción |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Especifica la cantidad de bytes de lectura y escritura al leer secuencialmente. |
## Métodos

| Método | Descripción |
| --- | --- |
| [canRead()](#canRead--) | Obtiene un valor que indica si la secuencia admite lectura. |
| [canSeek()](#canSeek--) | Obtiene un valor que indica si la secuencia admite búsqueda. |
| [canWrite()](#canWrite--) | Obtiene un valor que indica si la secuencia admite escritura. |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Limpia todos los búferes de esta secuencia y hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getLength()](#getLength--) | Obtiene o establece la longitud de la secuencia en bytes. |
| [getPosition()](#getPosition--) | Obtiene o establece la posición actual dentro de la secuencia. |
| [getStream()](#getStream--) | Obtiene la secuencia de datos. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado. |
| [hashCode()](#hashCode--) |  |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.psd.StreamContainer-boolean-) | Inserta el contenedor de secuencia en la posición especificada. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Obtiene un valor que indica si esta secuencia se elimina al cerrarse. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] bytes)](#read-byte---) | Lee bytes para llenar el búfer de bytes especificado. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Lee una secuencia de bytes de la secuencia actual y avanza la posición dentro de la secuencia por la cantidad de bytes leídos. |
| [readByte()](#readByte--) | Lee un byte de la secuencia y avanza la posición dentro de la secuencia en un byte, o devuelve -1 si está al final de la secuencia. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Guarda (copia) los datos de la secuencia al flujo especificado. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Guarda (copia) todos los datos de la secuencia al flujo especificado. |
| [save(OutputStream dstStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Guarda (copia) los datos de la secuencia al flujo especificado. |
| [save(String filePath)](#save-java.lang.String-) | Guarda (copia) los datos de la secuencia al flujo especificado. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Guarda (copia) los datos de la secuencia al flujo especificado. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Guarda (copia) los datos de la secuencia al flujo especificado. |
| [save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)](#save-internalized-com.aspose.ms.System.IO.Stream-int-long-) |  |
| [seek(long offset, int origin)](#seek-long-int-) | Establece la posición dentro de la secuencia actual. |
| [seekBegin()](#seekBegin--) | Establece la posición de la secuencia al comienzo de la secuencia. |
| [setLength(long value)](#setLength-long-) | Obtiene o establece la longitud de la secuencia en bytes. |
| [setPosition(long value)](#setPosition-long-) | Obtiene o establece la posición actual dentro de la secuencia. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Convierte los datos de la secuencia al  byte  array. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Convierte los datos de la secuencia al  byte  array. |
| [toString()](#toString--) |  |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | Realiza una conversión explícita de  com.aspose.imaging.StreamContainer  a  System.IO.Stream . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Escribe todos los bytes especificados en la secuencia. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Escribe una secuencia de bytes en la secuencia actual y avanza la posición actual dentro de esta secuencia por la cantidad de bytes escritos. |
| [writeByte(byte value)](#writeByte-byte-) | Escribe un byte en la posición actual de la secuencia y avanza la posición dentro de la secuencia en un byte. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | Copia los datos contenidos a otro  StreamContainer . |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | Copia los datos contenidos a otro  StreamContainer . |
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Inicializa una nueva instancia de la clase [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | El flujo. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Inicializa una nueva instancia de la clase [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | La secuencia de datos. |
| disposeStream | boolean | si se establece en  true  la secuencia se eliminará cuando el contenedor se elimine. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Inicializa una nueva instancia de la clase [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |
| disposeStream | boolean | si se establece en  true  elimina el flujo. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Especifica la cantidad de bytes de lectura y escritura al leer secuencialmente.

### canRead() {#canRead--}
```
public boolean canRead()
```


Obtiene un valor que indica si la secuencia admite lectura.

Valor:  true  si el flujo admite lectura; de lo contrario,  false .

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Obtiene un valor que indica si la secuencia admite búsqueda.

Valor:  true  si el flujo admite búsqueda; de lo contrario,  false .

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Obtiene un valor que indica si la secuencia admite escritura.

Valor:  true  si el flujo admite escritura; de lo contrario,  false .

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. Este método simplemente llama al método dispose.

### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| posicionInicial | long |  |
| disposeStream | boolean |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### dispose() {#dispose--}
```
public final void dispose()
```


Descarta la instancia actual.

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
### flush() {#flush--}
```
public void flush()
```


Limpia todos los búferes de esta secuencia y hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente.

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtiene un valor que indica si esta instancia está eliminada.

**Returns:**
boolean -  true  si está eliminado; de lo contrario,  false .
### getLength() {#getLength--}
```
public long getLength()
```


Obtiene o establece la longitud del flujo en bytes. Este valor es menor que el  System.IO.Stream.Length  por la posición inicial del flujo pasada en el constructor de StreamContainer.

Valor: La longitud del flujo.

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


Obtiene o establece la posición actual dentro del flujo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer.

Valor: La posición actual del flujo.

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


Obtiene la secuencia de datos.

Valor: El flujo de datos.

**Returns:**
java.io.InputStream
### getStream_internalized() {#getStream-internalized--}
```
public System.IO.Stream getStream_internalized()
```




**Returns:**
com.aspose.ms.System.IO.Stream
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
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
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.psd.StreamContainer-boolean-}
```
public final void insert(int position, StreamContainer stream, boolean disposeStream)
```


Inserta el contenedor de secuencia en la posición especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | int | La posición donde insertar. |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo a insertar. |
| disposeStream | boolean | si se establece en  true  elimina el flujo. |

### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Obtiene un valor que indica si esta secuencia se elimina al cerrarse.

Valor:  true  si el flujo se elimina al cerrar; de lo contrario,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


Lee bytes para llenar el búfer de bytes especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | byte[] | Los bytes a rellenar. |

**Returns:**
int - El número de bytes leídos. Este valor puede ser menor que el número de bytes en el búfer si no hay suficientes bytes en el flujo.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Lee una secuencia de bytes de la secuencia actual y avanza la posición dentro de la secuencia por la cantidad de bytes leídos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | byte[] | Una matriz de bytes. Cuando este método devuelve, el búfer contiene la matriz de bytes especificada con los valores entre  offset  y ( offset  +  count  - 1) reemplazados por los bytes leídos de la fuente actual. |
| offset | int | El desplazamiento de bytes basado en cero en  buffer  donde comenzar a almacenar los datos leídos del flujo actual. |
| count | int | El número máximo de bytes a leer del flujo actual. |

**Returns:**
int - El número total de bytes leídos en el búfer. Esto puede ser menor que el número de bytes solicitados si esa cantidad de bytes no está disponible actualmente, o cero (0) si se ha alcanzado el final del flujo.
### readByte() {#readByte--}
```
public int readByte()
```


Lee un byte de la secuencia y avanza la posición dentro de la secuencia en un byte, o devuelve -1 si está al final de la secuencia.

**Returns:**
int - El byte sin signo convertido a Int32, o -1 si está al final del flujo.
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Guarda (copia) los datos del flujo al flujo especificado. Utiliza el tamaño de búfer predeterminado  ReadWriteBytesCount  y el valor de  Length  del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | El flujo donde guardar los datos. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Guarda (copia) todos los datos del flujo al flujo especificado. Utiliza el valor de  Length  del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | El flujo donde guardar los datos. |
| bufferSize | int | El buffer. |

### save(OutputStream dstStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream dstStream, int bufferSize, long length)
```


Guarda (copia) los datos de la secuencia al flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dstStream | java.io.OutputStream | El flujo donde guardar los datos. |
| bufferSize | int | El tamaño del buffer. Por defecto se usa el valor [StreamContainer.READ\_WRITE\_BYTES\_COUNT](../../com.aspose.psd/streamcontainer\#READ-WRITE-BYTES-COUNT). |
| length | long | La longitud de los datos del flujo a copiar. Por defecto la longitud se establece al valor Length ([StreamContainer.getLength()](../../com.aspose.psd/streamcontainer\#getLength--)/[StreamContainer.setLength(long)](../../com.aspose.psd/streamcontainer\#setLength-long-)). |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Guarda (copia) los datos del flujo al flujo especificado. Utiliza el tamaño de búfer predeterminado  ReadWriteBytesCount  y el valor de  Length  del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo donde guardar los datos del flujo. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Guarda (copia) los datos del flujo al flujo especificado. Utiliza el valor Length del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo donde guardar los datos del flujo. |
| bufferSize | int | El tamaño del buffer. Por defecto se usa el valor ReadWriteBytesCount. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Guarda (copia) los datos de la secuencia al flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo donde guardar los datos del flujo. |
| bufferSize | int | El tamaño del buffer. Por defecto se usa el valor ReadWriteBytesCount. |
| longitud | long | La longitud de los datos del flujo a copiar. Por defecto la longitud se establece al valor Length. |

### save_internalized(System.IO.Stream destinationStream, int bufferSize, long length) {#save-internalized-com.aspose.ms.System.IO.Stream-int-long-}
```
public void save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destinationStream | com.aspose.ms.System.IO.Stream |  |
| bufferSize | int |  |
| longitud | long |  |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Establece la posición dentro de la secuencia actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| offset | long | Un desplazamiento de bytes relativo al parámetro origin. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer. |
| origin | int | Un valor del tipo [SeekOrigin](../../com.aspose.psd/seekorigin) que indica el punto de referencia usado para obtener la nueva posición. |

**Returns:**
long - La nueva posición dentro del flujo actual.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Establece la posición del flujo al comienzo del mismo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer.

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Obtiene o establece la longitud del flujo en bytes. Este valor es menor que el  System.IO.Stream.Length  por la posición inicial del flujo pasada en el constructor de StreamContainer.

Valor: La longitud del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Obtiene o establece la posición actual dentro del flujo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer.

Valor: La posición actual del flujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Convierte los datos de la secuencia al  byte  array.

**Returns:**
byte[] - Los datos del flujo convertidos al array de byte.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Convierte los datos de la secuencia al  byte  array.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | long | La posición desde la cual comenzar a leer bytes. |
| bytesCount | long | La cantidad de bytes a leer. |

**Returns:**
byte[] - Los datos del flujo convertidos al array de byte.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.psd.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


Realiza una conversión explícita de  com.aspose.imaging.StreamContainer  a  System.IO.Stream .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo. |

**Returns:**
com.aspose.ms.System.IO.Stream - El resultado de la conversión.
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

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Escribe todos los bytes especificados en la secuencia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | byte[] | Los bytes a escribir. |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Escribe una secuencia de bytes en la secuencia actual y avanza la posición actual dentro de esta secuencia por la cantidad de bytes escritos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | byte[] | Un array de bytes. Este método copia count bytes de buffer al flujo actual. |
| offset | int | El desplazamiento de bytes basado en cero en buffer en el que comenzar a copiar bytes al flujo actual. |
| count | int | El número de bytes que se escribirán en el flujo actual. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Escribe un byte en la posición actual de la secuencia y avanza la posición dentro de la secuencia en un byte.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | El byte a escribir en el flujo. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Copia los datos contenidos a otro  StreamContainer .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo al que copiar. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Copia los datos contenidos a otro  StreamContainer .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | El contenedor de flujo al que copiar. |
| longitud | long | La cantidad de bytes a escribir. |

