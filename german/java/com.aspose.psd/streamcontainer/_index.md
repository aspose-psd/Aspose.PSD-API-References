---
title: "StreamContainer"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt einen Stream‑Container dar, der den Stream enthält und Stream‑Verarbeitungsroutinen bereitstellt."
type: docs
weight: 103
url: /de/java/com.aspose.psd/streamcontainer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

Stellt einen Stream‑Container dar, der den Stream enthält und Stream‑Verarbeitungsroutinen bereitstellt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | Initialisiert eine neue Instanz der  StreamContainer  Klasse. |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) |  |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | Initialisiert eine neue Instanz der  StreamContainer  Klasse. |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | Gibt die Anzahl der Lese- und Schreibbytes beim sequentiellen Lesen an. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canRead()](#canRead--) | Gibt einen Wert zurück, der angibt, ob der Stream das Lesen unterstützt. |
| [canSeek()](#canSeek--) | Gibt einen Wert zurück, der angibt, ob der Stream das Suchen unterstützt. |
| [canWrite()](#canWrite--) | Gibt einen Wert zurück, der angibt, ob der Stream das Schreiben unterstützt. |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in einer try-with-resources-Anweisung verwendet werden. |
| [create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)](#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-) |  |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | Leert alle Puffer für diesen Stream und bewirkt, dass gepufferte Daten an das zugrunde liegende Gerät geschrieben werden. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [getLength()](#getLength--) | Liest oder setzt die Stream-Länge in Bytes. |
| [getPosition()](#getPosition--) | Liest oder setzt die aktuelle Position im Stream. |
| [getStream()](#getStream--) | Liest den Datenstream. |
| [getStream_internalized()](#getStream-internalized--) |  |
| [getSyncRoot()](#getSyncRoot--) | Liest ein Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren. |
| [hashCode()](#hashCode--) |  |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | Gibt einen Wert zurück, der angibt, ob dieser Stream beim Schließen freigegeben wird. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] bytes)](#read-byte---) | Liest Bytes, um den angegebenen Byte-Puffer zu füllen. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | Liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die gelesene Anzahl von Bytes. |
| [readByte()](#readByte--) | Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [save(String filePath)](#save-java.lang.String-) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [seek(long offset, int origin)](#seek-long-int-) | Setzt die Position im aktuellen Stream. |
| [seekBegin()](#seekBegin--) | Setzt die Stream-Position auf den Anfang des Streams. |
| [setLength(long value)](#setLength-long-) | Liest oder setzt die Stream-Länge in Bytes. |
| [setPosition(long value)](#setPosition-long-) | Liest oder setzt die aktuelle Position im Stream. |
| [takeAwayStream_internalized(StreamContainer src)](#takeAwayStream-internalized-com.aspose.psd.StreamContainer-) |  |
| [toBytes()](#toBytes--) | Konvertiert die Stream-Daten in das Byte-Array. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | Konvertiert die Stream-Daten in das Byte-Array. |
| [toString()](#toString--) |  |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.psd.StreamContainer-) | Führt eine explizite Konvertierung von  com.aspose.imaging.StreamContainer  zu  System.IO.Stream  durch. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] bytes)](#write-byte---) | Schreibt alle angegebenen Bytes in den Stream. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | Schreibt eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position in diesem Stream um die geschriebene Anzahl von Bytes. |
| [writeByte(byte value)](#writeByte-byte-) | Schreibt ein Byte an die aktuelle Position im Stream und verschiebt die Position im Stream um ein Byte. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.psd.StreamContainer-) | Kopiert die enthaltenen Daten in einen anderen  StreamContainer . |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.psd.StreamContainer-long-) | Kopiert die enthaltenen Daten in einen anderen  StreamContainer . |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


Initialisiert eine neue Instanz der  StreamContainer  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Stream. |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


Initialisiert eine neue Instanz der  StreamContainer  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Der Datenstream. |
| disposeStream | boolean | wenn auf  true  gesetzt, wird der Stream verworfen, wenn der Container verworfen wird. |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| disposeStream | boolean |  |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


Gibt die Anzahl der Lese- und Schreibbytes beim sequentiellen Lesen an.

### canRead() {#canRead--}
```
public boolean canRead()
```


Gibt einen Wert zurück, der angibt, ob der Stream das Lesen unterstützt.

Wert:  true  wenn der Stream das Lesen unterstützt; andernfalls  false .

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


Gibt einen Wert zurück, der angibt, ob der Stream das Suchen unterstützt.

Wert:  true  wenn der Stream das Suchen unterstützt; andernfalls  false .

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


Gibt einen Wert zurück, der angibt, ob der Stream das Schreiben unterstützt.

Wert:  true  wenn der Stream das Schreiben unterstützt; andernfalls  false .

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Implementiert das Closable-Interface und kann seit JDK 1.7 in der try-with-resources-Anweisung verwendet werden. Diese Methode ruft einfach die dispose-Methode auf.

### create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream) {#create-internalized-com.aspose.ms.System.IO.Stream-long-boolean-}
```
public static StreamContainer create_internalized(System.IO.Stream stream, long startPosition, boolean disposeStream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Gibt die aktuelle Instanz frei.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```


Leert alle Puffer für diesen Stream und bewirkt, dass gepufferte Daten an das zugrunde liegende Gerät geschrieben werden.

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


Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde.

**Returns:**
boolean -  true  wenn freigegeben; andernfalls,  false .
### getLength() {#getLength--}
```
public long getLength()
```


Liest oder setzt die Stream-Länge in Bytes. Dieser Wert ist kleiner als der  System.IO.Stream.Length  um die beim Konstruktor von StreamContainer übergebene Startposition des Streams.

Wert: Die Stream-Länge.

**Returns:**
long
### getPosition() {#getPosition--}
```
public long getPosition()
```


Liest oder setzt die aktuelle Position im Stream. Dieser Wert stellt den Versatz von der beim Konstruktor von StreamContainer übergebenen Startposition des Streams dar.

Wert: Die aktuelle Stream-Position.

**Returns:**
long
### getStream() {#getStream--}
```
public InputStream getStream()
```


Liest den Datenstream.

Wert: Der Daten-Stream.

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


Liest ein Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren.

Wert: Das Objekt, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren.

**Returns:**
java.lang.Object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


Gibt einen Wert zurück, der angibt, ob dieser Stream beim Schließen freigegeben wird.

Wert:  true  wenn der Stream beim Schließen verworfen wird; andernfalls  false .

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


Liest Bytes, um den angegebenen Byte-Puffer zu füllen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bytes | byte[] | Die auszufüllenden Bytes. |

**Returns:**
int - Die Anzahl gelesener Bytes. Dieser Wert kann kleiner sein als die Anzahl Bytes im Puffer, wenn nicht genug Bytes im Stream vorhanden sind.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


Liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die gelesene Anzahl von Bytes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffer | byte[] | Ein Array von Bytes. Wenn diese Methode zurückkehrt, enthält der Puffer das angegebene Byte-Array, wobei die Werte zwischen  offset  und ( offset  +  count  - 1) durch die aus der aktuellen Quelle gelesenen Bytes ersetzt wurden. |
| Versatz | int | Der nullbasierte Byte-Offset im  buffer , an dem das Speichern der aus dem aktuellen Stream gelesenen Daten beginnen soll. |
| count | int | Die maximale Anzahl zu lesender Bytes aus dem aktuellen Stream. |

**Returns:**
int - Die Gesamtzahl der in den Puffer gelesenen Bytes. Dies kann weniger sein als die angeforderte Anzahl, wenn nicht so viele Bytes verfügbar sind, oder null (0), wenn das Ende des Streams erreicht wurde.
### readByte() {#readByte--}
```
public int readByte()
```


Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist.

**Returns:**
int - Das unsigned Byte, in ein Int32 umgewandelt, oder -1, wenn das Ende des Streams erreicht ist.
### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße  ReadWriteBytesCount  und den Stream‑Wert  Length .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Der Stream, in den die Daten gespeichert werden sollen. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet den Stream‑Wert  Length .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Der Stream, in den die Daten gespeichert werden sollen. |
| bufferSize | int | Der Puffer. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


Speichert (kopiert) die Daten des Streams in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | Der Stream, in den die Daten gespeichert werden sollen. |
| bufferSize | int | Die Puffergröße. Standardmäßig wird der Wert  ReadWriteBytesCount  verwendet. |
| length | long | Die Länge der zu kopierenden Stream-Daten. Standardmäßig ist die Länge auf den Wert  Length  gesetzt. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße  ReadWriteBytesCount  und den Stream‑Wert  Length .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, in dem die Stream-Daten gespeichert werden sollen. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet den Wert  Length .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, in dem die Stream-Daten gespeichert werden sollen. |
| bufferSize | int | Die Puffergröße. Standardmäßig wird der Wert  ReadWriteBytesCount  verwendet. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


Speichert (kopiert) die Daten des Streams in den angegebenen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad, in dem die Stream-Daten gespeichert werden sollen. |
| bufferSize | int | Die Puffergröße. Standardmäßig wird der Wert  ReadWriteBytesCount  verwendet. |
| length | long | Die Länge der zu kopierenden Stream-Daten. Standardmäßig ist die Länge auf den Wert  Length  gesetzt. |

### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


Setzt die Position im aktuellen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Versatz | long | Ein Byte-Offset relativ zum Parameter  origin . Dieser Wert stellt den Offset von der im Konstruktor von StreamContainer übergebenen Startposition des Streams dar. |
| Ursprung | int | Ein Wert vom Typ System.IO.SeekOrigin, der den Referenzpunkt angibt, der zum Ermitteln der neuen Position verwendet wird. |

**Returns:**
long – Die neue Position innerhalb des aktuellen Streams.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


Setzt die Stream-Position auf den Anfang des Streams. Dieser Wert stellt den Offset von der im Konstruktor von StreamContainer übergebenen Startposition des Streams dar.

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


Liest oder setzt die Stream-Länge in Bytes. Dieser Wert ist kleiner als der  System.IO.Stream.Length  um die beim Konstruktor von StreamContainer übergebene Startposition des Streams.

Wert: Die Stream-Länge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Liest oder setzt die aktuelle Position im Stream. Dieser Wert stellt den Versatz von der beim Konstruktor von StreamContainer übergebenen Startposition des Streams dar.

Wert: Die aktuelle Stream-Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### takeAwayStream_internalized(StreamContainer src) {#takeAwayStream-internalized-com.aspose.psd.StreamContainer-}
```
public static StreamContainer takeAwayStream_internalized(StreamContainer src)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer)
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


Konvertiert die Stream-Daten in das Byte-Array.

**Returns:**
byte[] – Die Stream-Daten, konvertiert in das  byte  Array.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


Konvertiert die Stream-Daten in das Byte-Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | long | Die Position, ab der Bytes gelesen werden sollen. |
| bytesCount | long | Die zu lesende Byte-Anzahl. |

**Returns:**
byte[] – Die Stream-Daten, konvertiert in das  byte  Array.
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


Führt eine explizite Konvertierung von  com.aspose.imaging.StreamContainer  zu  System.IO.Stream  durch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container. |

**Returns:**
com.aspose.ms.System.IO.Stream – Das Ergebnis der Konvertierung.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


Schreibt alle angegebenen Bytes in den Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bytes | byte[] | Die zu schreibenden Bytes. |

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


Schreibt eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position in diesem Stream um die geschriebene Anzahl von Bytes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffer | byte[] | Ein Array von Bytes. Diese Methode kopiert  count  Bytes von  buffer  in den aktuellen Stream. |
| Versatz | int | Der nullbasierte Byte-Offset in  buffer , an dem das Kopieren von Bytes in den aktuellen Stream beginnen soll. |
| count | int | Die Anzahl der Bytes, die in den aktuellen Stream geschrieben werden sollen. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Schreibt ein Byte an die aktuelle Position im Stream und verschiebt die Position im Stream um ein Byte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | Das Byte, das in den Stream geschrieben werden soll. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.psd.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


Kopiert die enthaltenen Daten in einen anderen  StreamContainer .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container, in den kopiert werden soll. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.psd.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


Kopiert die enthaltenen Daten in einen anderen  StreamContainer .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Der Stream-Container, in den kopiert werden soll. |
| length | long | Die zu schreibende Byte-Anzahl. |

