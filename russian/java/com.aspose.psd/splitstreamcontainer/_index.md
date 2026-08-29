---
title: "SplitStreamContainer"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет разделённый контейнер потока, который содержит поток и предоставляет процедуры обработки потока."
type: docs
weight: 102
url: /ru/java/com.aspose.psd/splitstreamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.StreamContainer](../../com.aspose.psd/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

Представляет разделённый контейнер потока, который содержит поток и предоставляет процедуры обработки потока.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | Инициализирует новый экземпляр класса [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | Инициализирует новый экземпляр класса [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-) | Инициализирует новый экземпляр класса [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer). |
## Поля

| Поле | Описание |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Указывает количество байтов для чтения и записи при последовательном чтении. |
## Методы

| Метод | Описание |
| --- | --- |
| [canRead()](#canRead--) | Возвращает значение, указывающее, поддерживает ли поток чтение. |
| [canSeek()](#canSeek--) | Возвращает значение, указывающее, поддерживает ли поток поиск. |
| [canWrite()](#canWrite--) | Возвращает значение, указывающее, поддерживает ли поток запись. |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Очищает все буферы этого потока и заставляет любые буферизованные данные записаться в базовое устройство. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getLength()](#getLength--) | Получает или задаёт длину потока в байтах. |
| [getPosition()](#getPosition--) | Получает или задаёт текущую позицию в потоке. |
| [getStream()](#getStream--) | Получает поток данных. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который может использоваться для синхронизации доступа к синхронизированному ресурсу. |
| [hashCode()](#hashCode--) |  |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.psd.StreamContainer-boolean-) | Вставляет контейнер потока в указанную позицию. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Возвращает значение, указывающее, будет ли поток освобождён при закрытии. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] bytes)](#read-byte---) | Считывает байты, заполняя указанный буфер байтов. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Считывает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| [readByte()](#readByte--) | Считывает байт из потока и перемещает позицию в потоке на один байт, либо возвращает -1, если достигнут конец потока. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Сохраняет (копирует) данные потока в указанный поток. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Сохраняет (копирует) все данные потока в указанный поток. |
| [save(OutputStream dstStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Сохраняет (копирует) данные потока в указанный поток. |
| [save(String filePath)](#save-java.lang.String-) | Сохраняет (копирует) данные потока в указанный поток. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Сохраняет (копирует) данные потока в указанный поток. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Сохраняет (копирует) данные потока в указанный поток. |
| [save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)](#save-internalized-com.aspose.ms.System.IO.Stream-int-long-) |  |
| [seek(long offset, int origin)](#seek-long-int-) | Устанавливает позицию в текущем потоке. |
| [seekBegin()](#seekBegin--) | Устанавливает позицию потока в начало потока. |
| [setLength(long value)](#setLength-long-) | Получает или задаёт длину потока в байтах. |
| [setPosition(long value)](#setPosition-long-) | Получает или задаёт текущую позицию в потоке. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Преобразует данные потока в  byte  массив. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Преобразует данные потока в  byte  массив. |
| [toString()](#toString--) |  |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | Выполняет явное преобразование из  com.aspose.imaging.StreamContainer  в  System.IO.Stream . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Записывает все указанные байты в поток. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов. |
| [writeByte(byte value)](#writeByte-byte-) | Записывает байт в текущую позицию в потоке и перемещает позицию в потоке на один байт. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | Копирует содержащиеся данные в другой  StreamContainer . |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | Копирует содержащиеся данные в другой  StreamContainer . |
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


Инициализирует новый экземпляр класса [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


Инициализирует новый экземпляр класса [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток данных. |
| disposeStream | boolean | если установить в  true  поток будет освобождён при освобождении контейнера. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.psd.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


Инициализирует новый экземпляр класса [SplitStreamContainer](../../com.aspose.psd/splitstreamcontainer).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |
| disposeStream | boolean | если установить в  true  освобождает поток. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Указывает количество байтов для чтения и записи при последовательном чтении.

### canRead() {#canRead--}
```
public boolean canRead()
```


Возвращает значение, указывающее, поддерживает ли поток чтение.

Значение:  true  если поток поддерживает чтение; иначе,  false .

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Возвращает значение, указывающее, поддерживает ли поток поиск.

Значение:  true  если поток поддерживает поиск; иначе,  false .

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Возвращает значение, указывающее, поддерживает ли поток запись.

Значение:  true  если поток поддерживает запись; иначе,  false .

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Реализует интерфейс Closable и может использоваться в операторе try-with-resources, начиная с JDK 1.7. Этот метод просто вызывает метод dispose.

### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| startPosition | long |  |
| disposeStream | boolean |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает текущий экземпляр.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```


Очищает все буферы этого потока и заставляет любые буферизованные данные записаться в базовое устройство.

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


Получает значение, указывающее, освобожден ли этот экземпляр.

**Returns:**
boolean -  true  если освобождено; иначе,  false .
### getLength() {#getLength--}
```
public long getLength()
```


Получает или задает длину потока в байтах. Это значение меньше, чем  System.IO.Stream.Length  на начальную позицию потока, переданную в конструкторе StreamContainer.

Значение: Длина потока.

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


Получает или задает текущую позицию в потоке. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer.

Значение: Текущая позиция потока.

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


Получает поток данных.

Значение: Поток данных.

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


Получает объект, который может использоваться для синхронизации доступа к синхронизированному ресурсу.

Значение: Объект, который может использоваться для синхронизации доступа к синхронизированному ресурсу.

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


Вставляет контейнер потока в указанную позицию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | int | Позиция для вставки. |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока для вставки. |
| disposeStream | boolean | если установить в  true  освобождает поток. |

### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Возвращает значение, указывающее, будет ли поток освобождён при закрытии.

Значение:  true  если поток освобождается при закрытии; иначе,  false .

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


Считывает байты, заполняя указанный буфер байтов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | byte[] | Байты для заполнения. |

**Returns:**
int - Количество прочитанных байтов. Это значение может быть меньше количества байтов в буфере, если в потоке недостаточно байтов.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Считывает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| буфер | byte[] | Массив байтов. После возврата этого метода буфер содержит указанный массив байтов, где значения между  offset  и ( offset  +  count  - 1) заменены байтами, прочитанными из текущего источника. |
| смещение | int | Нулевой байтовый смещение в  buffer , с которого начинать сохранять данные, прочитанные из текущего потока. |
| count | int | Максимальное количество байтов, которое будет прочитано из текущего потока. |

**Returns:**
int - Общее количество байтов, прочитанных в буфер. Это может быть меньше запрошенного количества байтов, если их сейчас недоступно, или ноль (0), если достигнут конец потока.
### readByte() {#readByte--}
```
public int readByte()
```


Считывает байт из потока и перемещает позицию в потоке на один байт, либо возвращает -1, если достигнут конец потока.

**Returns:**
int - Беззнаковый байт, преобразованный в Int32, или -1, если достигнут конец потока.
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию  ReadWriteBytesCount  и значение длины потока  Length .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Поток, в который сохраняются данные. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Сохраняет (копирует) все данные потока в указанный поток. Использует значение длины потока  Length .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Поток, в который сохраняются данные. |
| bufferSize | int | Буфер. |

### save(OutputStream dstStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream dstStream, int bufferSize, long length)
```


Сохраняет (копирует) данные потока в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dstStream | java.io.OutputStream | Поток, в который сохраняются данные. |
| bufferSize | int | Размер буфера. По умолчанию используется значение [StreamContainer.READ\_WRITE\_BYTES\_COUNT](../../com.aspose.psd/streamcontainer\#READ-WRITE-BYTES-COUNT). |
| length | long | Длина данных потока для копирования. По умолчанию длина устанавливается в значение Length ([StreamContainer.getLength()](../../com.aspose.psd/streamcontainer\#getLength--)/[StreamContainer.setLength(long)](../../com.aspose.psd/streamcontainer\#setLength-long-)). |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию  ReadWriteBytesCount  и значение длины потока  Length .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу, в который сохраняются данные потока. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Сохраняет (копирует) данные потока в указанный поток. Использует значение Length потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу, в который сохраняются данные потока. |
| bufferSize | int | Размер буфера. По умолчанию используется значение ReadWriteBytesCount. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Сохраняет (копирует) данные потока в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу, в который сохраняются данные потока. |
| bufferSize | int | Размер буфера. По умолчанию используется значение ReadWriteBytesCount. |
| length | long | Длина данных потока для копирования. По умолчанию длина устанавливается в значение Length. |

### save_internalized(System.IO.Stream destinationStream, int bufferSize, long length) {#save-internalized-com.aspose.ms.System.IO.Stream-int-long-}
```
public void save_internalized(System.IO.Stream destinationStream, int bufferSize, long length)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destinationStream | com.aspose.ms.System.IO.Stream |  |
| bufferSize | int |  |
| length | long |  |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Устанавливает позицию в текущем потоке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| смещение | long | Смещение в байтах относительно параметра origin. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| origin | int | Значение типа [SeekOrigin](../../com.aspose.psd/seekorigin) указывающее точку отсчёта, используемую для получения новой позиции. |

**Returns:**
long — Новая позиция внутри текущего потока.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Устанавливает позицию потока в начало потока. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer.

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Получает или задает длину потока в байтах. Это значение меньше, чем  System.IO.Stream.Length  на начальную позицию потока, переданную в конструкторе StreamContainer.

Значение: Длина потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Получает или задает текущую позицию в потоке. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer.

Значение: Текущая позиция потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Преобразует данные потока в  byte  массив.

**Returns:**
byte[] — Данные потока, преобразованные в массив byte.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Преобразует данные потока в  byte  массив.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция, с которой начинать чтение байтов. |
| bytesCount | long | Количество байтов для чтения. |

**Returns:**
byte[] — Данные потока, преобразованные в массив byte.
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


Выполняет явное преобразование из  com.aspose.imaging.StreamContainer  в  System.IO.Stream .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |

**Returns:**
com.aspose.ms.System.IO.Stream — Результат преобразования.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Записывает все указанные байты в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| байты | byte[] | Байты для записи. |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| буфер | byte[] | Массив байтов. Этот метод копирует count байтов из buffer в текущий поток. |
| смещение | int | Нулевой базовый смещение в байтах в buffer, с которого начинать копирование байтов в текущий поток. |
| count | int | Количество байтов, которое будет записано в текущий поток. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Записывает байт в текущую позицию в потоке и перемещает позицию в потоке на один байт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte | Байт для записи в поток. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Копирует содержащиеся данные в другой  StreamContainer .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока, в который копировать. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Копирует содержащиеся данные в другой  StreamContainer .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока, в который копировать. |
| length | long | Количество байтов для записи. |

