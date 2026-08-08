---
title: "FileStreamContainer"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Ayudante para el procesamiento de flujos de archivo."
type: docs
weight: 44
url: /es/java/com.aspose.psd/filestreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

Ayudante para el procesamiento de flujos de archivo.
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
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | Crea un nuevo flujo de archivo. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Limpia todos los búferes de esta secuencia y hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getFilePath()](#getFilePath--) | Obtiene la ruta del archivo. |
| [getLength()](#getLength--) | Obtiene o establece la longitud de la secuencia en bytes. |
| [getPosition()](#getPosition--) | Obtiene o establece la posición actual dentro de la secuencia. |
| [getStream()](#getStream--) | Obtiene la secuencia de datos. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado. |
| [hashCode()](#hashCode--) |  |
| [isCreated()](#isCreated--) | Obtiene un valor que indica si el flujo fue creado explícitamente. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Obtiene un valor que indica si esta secuencia se elimina al cerrarse. |
| [isTemporal()](#isTemporal--) | Obtiene o establece un valor que indica si el flujo es temporal. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | Abre un flujo de archivo existente. |
| [openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)](#openFileStream-internalized-java.lang.String-boolean-) | Abre un flujo de archivo existente. |
| [read(byte[] bytes)](#read-byte---) | Lee bytes para llenar el búfer de bytes especificado. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Lee una secuencia de bytes de la secuencia actual y avanza la posición dentro de la secuencia por la cantidad de bytes leídos. |
| [readByte()](#readByte--) | Lee un byte de la secuencia y avanza la posición dentro de la secuencia en un byte, o devuelve -1 si está al final de la secuencia. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Guarda (copia) los datos de la secuencia al flujo especificado. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Guarda (copia) todos los datos de la secuencia al flujo especificado. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Guarda (copia) los datos de la secuencia al flujo especificado. |
| [save(String filePath)](#save-java.lang.String-) | Guarda (copia) los datos de la secuencia al flujo especificado. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Guarda (copia) los datos de la secuencia al flujo especificado. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Guarda (copia) los datos de la secuencia al flujo especificado. |
| [seek(long offset, int origin)](#seek-long-int-) | Establece la posición dentro de la secuencia actual. |
| [seekBegin()](#seekBegin--) | Establece la posición de la secuencia al comienzo de la secuencia. |
| [setLength(long value)](#setLength-long-) | Obtiene o establece la longitud de la secuencia en bytes. |
| [setPosition(long value)](#setPosition-long-) | Obtiene o establece la posición actual dentro de la secuencia. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | Obtiene o establece un valor que indica si el flujo es temporal. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Convierte los datos de la secuencia al  byte  array. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Convierte los datos de la secuencia al  byte  array. |
| [toString()](#toString--) |  |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.psd.FileStreamContainer-) | Realiza una conversión explícita de [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) a FileInputStream. |
| [to_FileStream_internalized(FileStreamContainer fileStreamContainer)](#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.psd.FileStreamContainer-) | Realiza una conversión explícita de [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) a java.io.InputStream. |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | Realiza una conversión explícita de  com.aspose.imaging.StreamContainer  a  System.IO.Stream . |
| [to_Stream_internalized(FileStreamContainer fileStreamContainer)](#to-Stream-internalized-com.aspose.psd.FileStreamContainer-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Escribe todos los bytes especificados en la secuencia. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Escribe una secuencia de bytes en la secuencia actual y avanza la posición actual dentro de esta secuencia por la cantidad de bytes escritos. |
| [writeByte(byte value)](#writeByte-byte-) | Escribe un byte en la posición actual de la secuencia y avanza la posición dentro de la secuencia en un byte. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | Copia los datos contenidos a otro  StreamContainer . |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | Copia los datos contenidos a otro  StreamContainer . |
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

### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


Crea un nuevo flujo de archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileLocation | java.lang.String | La ubicación del archivo. |
| isTemporal | boolean | Si se establece en  true  el contenedor de flujo de archivo es temporal. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
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
### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


Obtiene la ruta del archivo.

Valor: La ruta del archivo.

**Returns:**
java.lang.String
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
### isCreated() {#isCreated--}
```
public final boolean isCreated()
```


Obtiene un valor que indica si el flujo fue creado explícitamente.

Valor:  true  si el flujo fue creado explícitamente; de lo contrario,  false .

**Returns:**
boolean
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Obtiene un valor que indica si esta secuencia se elimina al cerrarse.

Valor:  true  si el flujo se elimina al cerrar; de lo contrario,  false .

**Returns:**
boolean
### isTemporal() {#isTemporal--}
```
public final boolean isTemporal()
```


Obtiene o establece un valor que indica si el flujo es temporal.

Valor:  true  si el flujo es temporal; de lo contrario,  false .

--------------------

Un flujo temporal se eliminará a sí mismo cuando se deseche. Si el flujo está basado en memoria, esta propiedad no tiene efecto. El flujo puede marcarse como temporal o persistente en caso de que haya sido creado explícitamente; de lo contrario, se lanzará la excepción apropiada.

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




### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


Abre un flujo de archivo existente. Si el flujo de archivo no existe, se lanza la excepción apropiada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileLocation | java.lang.String | La ubicación del archivo. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
### openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams) {#openFileStream-internalized-java.lang.String-boolean-}
```
public static FileStreamContainer openFileStream_internalized(String fileLocation, boolean disposeDuplicatedStreams)
```


Abre un flujo de archivo existente. Si el flujo de archivo no existe, se lanza la excepción apropiada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileLocation | java.lang.String | La ubicación del archivo. |
| disposeDuplicatedStreams | boolean | si se establece en  true  desecha los flujos duplicados. |

**Returns:**
[FileStreamContainer](../../com.aspose.psd/filestreamcontainer) - The file stream container.
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

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Guarda (copia) los datos de la secuencia al flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | El flujo donde guardar los datos. |
| bufferSize | int | El tamaño del buffer. Por defecto se usa el valor ReadWriteBytesCount. |
| longitud | long | La longitud de los datos del flujo a copiar. Por defecto la longitud se establece al valor Length. |

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

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Establece la posición dentro de la secuencia actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| offset | long | Un desplazamiento de bytes relativo al parámetro origin. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer. |
| origin | int | Un valor de tipo  System.IO.SeekOrigin  que indica el punto de referencia usado para obtener la nueva posición. |

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

### setTemporal(boolean value) {#setTemporal-boolean-}
```
public final void setTemporal(boolean value)
```


Obtiene o establece un valor que indica si el flujo es temporal.

Valor:  true  si el flujo es temporal; de lo contrario,  false .

--------------------

Un flujo temporal se eliminará a sí mismo cuando se deseche. Si el flujo está basado en memoria, esta propiedad no tiene efecto. El flujo puede marcarse como temporal o persistente en caso de que haya sido creado explícitamente; de lo contrario, se lanzará la excepción apropiada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.psd.FileStreamContainer-}
```
public static FileInputStream to_FileStream(FileStreamContainer fileStreamContainer)
```


Realiza una conversión explícita de [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) a FileInputStream.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | El contenedor de flujo de archivo. |

**Returns:**
java.io.FileInputStream - El resultado de la conversión.
### to_FileStream_internalized(FileStreamContainer fileStreamContainer) {#to-FileStream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) |  |

**Returns:**
com.aspose.ms.System.IO.FileStream
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.psd.FileStreamContainer-}
```
public static InputStream to_Stream(FileStreamContainer fileStreamContainer)
```


Realiza una conversión explícita de [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) a java.io.InputStream.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) | El contenedor de flujo de archivo. |

**Returns:**
java.io.InputStream - El resultado de la conversión.
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
### to_Stream_internalized(FileStreamContainer fileStreamContainer) {#to-Stream-internalized-com.aspose.psd.FileStreamContainer-}
```
public static System.IO.Stream to_Stream_internalized(FileStreamContainer fileStreamContainer)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.psd/filestreamcontainer) |  |

**Returns:**
com.aspose.ms.System.IO.Stream
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

