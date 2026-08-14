---
title: "SplitStreamContainer Klasse"
type: docs
weight: 4220
url: /de/python-net/aspose.psd/splitstreamcontainer/
---

**Summary:** Represents split stream container which contains the stream and provides stream processing routines.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SplitStreamContainer

**Inheritance:** StreamContainer

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [SplitStreamContainer(stream)](#SplitStreamContainer_stream_1) | Initialisiert eine neue Instanz der [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) Klasse. |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_2) | Initialisiert eine neue Instanz der [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) Klasse. |
| [SplitStreamContainer(stream, dispose_stream)](#SplitStreamContainer_stream_dispose_stream_3) | Initialisiert eine neue Instanz der [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [statisch] | int | r | Gibt die Anzahl der Lese- und Schreibbytes beim sequentiellen Lesen an. |
| can_read | bool | r | Gibt einen Wert zurück, der angibt, ob der Stream das Lesen unterstützt. |
| can_seek | bool | r | Gibt einen Wert zurück, der angibt, ob der Stream das Suchen unterstützt. |
| can_write | bool | r | Gibt einen Wert zurück, der angibt, ob der Stream das Schreiben unterstützt. |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| is_stream_disposed_on_close | bool | r | Gibt einen Wert zurück, der angibt, ob dieser Stream beim Schließen freigegeben wird. |
| Länge | long | r/w | Liest oder setzt die Streamlänge in Bytes. Dieser Wert ist kleiner als die durch die Startposition des Streams, die im Konstruktor von StreamContainer übergeben wurde. |
| Position | long | r/w | Liest oder setzt die aktuelle Position im Stream. Dieser Wert stellt den Offset zur Startposition des Streams dar, die im Konstruktor von StreamContainer übergeben wurde. |
| Strom | _io.BufferedRandom | r | Liest den Datenstream. |
| sync_root | object | r | Gibt ein Objekt zurück, das verwendet werden kann, um den Zugriff auf die synchronisierte Ressource zu synchronisieren. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| flush() | Löscht alle Puffer für diesen Stream und sorgt dafür, dass alle gepufferten Daten auf das zugrunde liegende Gerät geschrieben werden. |
| [insert(position, stream, dispose_stream)](#insert_position_stream_dispose_stream_1) | Fügt den Stream-Container an der angegebenen Position ein. |
| [read(buffer, offset, count)](#read_buffer_offset_count_2) | Liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die gelesene Anzahl von Bytes. |
| [read(bytes)](#read_bytes_3) | Liest Bytes, um den angegebenen Byte-Puffer zu füllen. |
| [read_byte()](#read_byte__4) | Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist. |
| [save(destination_stream)](#save_destination_stream_5) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) und den Wert des Streams [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_6) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet den Wert des Streams [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_7) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [save(file_path)](#save_file_path_8) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) und den Wert des Streams [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_9) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet den Wert des Streams [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_10) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| [seek(offset, origin)](#seek_offset_origin_11) | Setzt die Position im aktuellen Stream. |
| seek_begin() | Setzt die Stream-Position auf den Anfang des Streams. Dieser Wert stellt den Offset von der beim StreamContainer-Konstruktor übergebenen Startposition des Streams dar. |
| [to_bytes()](#to_bytes__12) | Konvertiert die Stream-Daten in ein int-Array. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_13) | Konvertiert die Stream-Daten in ein int-Array. |
| [write(buffer, offset, count)](#write_buffer_offset_count_14) | Schreibt eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position in diesem Stream um die geschriebene Anzahl von Bytes. |
| [write(bytes)](#write_bytes_15) | Schreibt alle angegebenen Bytes in den Stream. |
| [write_byte(value)](#write_byte_value_16) | Schreibt ein Byte an die aktuelle Position im Stream und verschiebt die Position im Stream um ein Byte. |
| [write_to(stream_container)](#write_to_stream_container_17) | Kopiert die enthaltenen Daten in einen anderen [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |
| [write_to(stream_container, length)](#write_to_stream_container_length_18) | Kopiert die enthaltenen Daten in einen anderen [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/). |


### Constructor: SplitStreamContainer(stream) {#SplitStreamContainer_stream_1}


```
 SplitStreamContainer(stream) 
```

Initialisiert eine neue Instanz der [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_2}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Initialisiert eine neue Instanz der [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Datenstrom. |
| dispose_stream | bool | Wenn auf <c>true</c> gesetzt, wird der Stream freigegeben, wenn der Container freigegeben wird. |

### Constructor: SplitStreamContainer(stream, dispose_stream) {#SplitStreamContainer_stream_dispose_stream_3}


```
 SplitStreamContainer(stream, dispose_stream) 
```

Initialisiert eine neue Instanz der [SplitStreamContainer](/psd/python-net/aspose.psd/splitstreamcontainer/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Datenstrom. |
| dispose_stream | bool | Wenn auf <c>true</c> gesetzt, wird der Stream freigegeben, wenn der Container freigegeben wird. |

### Method: insert(position, stream, dispose_stream) {#insert_position_stream_dispose_stream_1}


```
 insert(position, stream, dispose_stream) 
```

Fügt den Stream-Container an der angegebenen Position ein.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | int | Die Position, an die eingefügt werden soll. |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der einzufügende Stream-Container. |
| dispose_stream | bool | Wenn auf <c>true</c> gesetzt, wird der Stream freigegeben. |

### Method: read(buffer, offset, count) {#read_buffer_offset_count_2}


```
 read(buffer, offset, count) 
```

Liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die gelesene Anzahl von Bytes.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Puffer | byte | Ein Array von Bytes. Wenn diese Methode zurückkehrt, enthält der Puffer das angegebene Byte-Array, wobei die Werte zwischen <paramref name="offset" /> und (<paramref name="offset" /> + <paramref name="count" /> - 1) durch die aus der aktuellen Quelle gelesenen Bytes ersetzt wurden. |
| offset | int | Der nullbasierte Byte-Offset in <paramref name="buffer" />, bei dem das Speichern der aus dem aktuellen Stream gelesenen Daten beginnen soll. |
| Anzahl | int | Die maximale Anzahl von Bytes, die aus dem aktuellen Stream gelesen werden sollen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die Gesamtzahl der in den Puffer gelesenen Bytes. Diese kann kleiner sein als die angeforderte Anzahl von Bytes, wenn nicht so viele Bytes verfügbar sind, oder null (0), wenn das Ende des Streams erreicht wurde. |


### Method: read(bytes) {#read_bytes_3}


```
 read(bytes) 
```

Liest Bytes, um den angegebenen Byte-Puffer zu füllen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Bytes | byte | Die zu füllenden Bytes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die Anzahl gelesener Bytes. Dieser Wert kann kleiner sein als die Anzahl der Bytes im Puffer, wenn im Stream nicht genügend Bytes vorhanden sind. |


### Method: read_byte() {#read_byte__4}


```
 read_byte() 
```

Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Das vorzeichenlose Byte, in ein Int32 umgewandelt, oder -1, wenn das Ende des Streams erreicht ist. |


### Method: save(destination_stream) {#save_destination_stream_5}


```
 save(destination_stream) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) und den Wert des Streams [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Der Stream, in dem die Daten gespeichert werden sollen. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_6}


```
 save(destination_stream, buffer_size) 
```

Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet den Wert des Streams [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Der Stream, in dem die Daten gespeichert werden sollen. |
| buffer_size | int | Der Puffer. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_7}


```
 save(destination_stream, buffer_size, length) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | Der Stream, in dem die Daten gespeichert werden sollen. |
| buffer_size | int | Die Puffergröße. Standardmäßig wird der Wert ReadWriteBytesCount verwendet. |
| length | long | Die Länge der zu kopierenden Stream-Daten. Standardmäßig wird die Länge auf den Wert [SplitStreamContainer.length](/psd/python-net/aspose.psd/splitstreamcontainer/) gesetzt. |

### Method: save(file_path) {#save_file_path_8}


```
 save(file_path) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) und den Wert des Streams [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Stream-Daten gespeichert werden sollen. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_9}


```
 save(file_path, buffer_size) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet den Wert des Streams [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Stream-Daten gespeichert werden sollen. |
| buffer_size | int | Die Puffergröße. Standardmäßig wird der Wert [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) verwendet. |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_10}


```
 save(file_path, buffer_size, length) 
```

Speichert (kopiert) die Daten des Streams in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Stream-Daten gespeichert werden sollen. |
| buffer_size | int | Die Puffergröße. Standardmäßig wird der Wert [StreamContainer.READ_WRITE_BYTES_COUNT](/psd/python-net/aspose.psd/streamcontainer/) verwendet. |
| length | long | Die Länge der zu kopierenden Stream-Daten. Standardmäßig wird die Länge auf den Wert [StreamContainer.length](/psd/python-net/aspose.psd/streamcontainer/) gesetzt. |

### Method: seek(offset, origin) {#seek_offset_origin_11}


```
 seek(offset, origin) 
```

Setzt die Position im aktuellen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| offset | long | Ein Byte-Offset relativ zum Parameter <paramref name="origin" />. Dieser Wert stellt den Offset von der im Konstruktor von StreamContainer übergebenen Startposition des Streams dar. |
| origin | [SeekOrigin](/psd/python-net/aspose.psd/seekorigin) | Ein Wert vom Typ SeekOrigin, der den Bezugspunkt angibt, der zur Ermittlung der neuen Position verwendet wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| long | Die neue Position innerhalb des aktuellen Streams. |


### Method: to_bytes() {#to_bytes__12}


```
 to_bytes() 
```

Konvertiert die Stream-Daten in ein int-Array.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte | Die Stream-Daten, konvertiert in das int-Array. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_13}


```
 to_bytes(position, bytes_count) 
```

Konvertiert die Stream-Daten in ein int-Array.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Position | long | Die Position, ab der Bytes gelesen werden sollen. |
| bytes_count | long | Die zu lesende Byte-Anzahl. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte | Die Stream-Daten, konvertiert in das int-Array. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_14}


```
 write(buffer, offset, count) 
```

Schreibt eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position in diesem Stream um die geschriebene Anzahl von Bytes.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Puffer | byte | Ein Array von Bytes. Diese Methode kopiert <paramref name="count" /> Bytes von <paramref name="buffer" /> in den aktuellen Stream. |
| offset | int | Der nullbasierte Byte-Offset in <paramref name="buffer" />, bei dem das Kopieren von Bytes in den aktuellen Stream beginnen soll. |
| Anzahl | int | Die Anzahl der Bytes, die in den aktuellen Stream geschrieben werden sollen. |

### Method: write(bytes) {#write_bytes_15}


```
 write(bytes) 
```

Schreibt alle angegebenen Bytes in den Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Bytes | byte | Die zu schreibenden Bytes. |

### Method: write_byte(value) {#write_byte_value_16}


```
 write_byte(value) 
```

Schreibt ein Byte an die aktuelle Position im Stream und verschiebt die Position im Stream um ein Byte.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | byte | Das Byte, das in den Stream geschrieben werden soll. |

### Method: write_to(stream_container) {#write_to_stream_container_17}


```
 write_to(stream_container) 
```

Kopiert die enthaltenen Daten in einen anderen [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Container, in den kopiert werden soll. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_18}


```
 write_to(stream_container, length) 
```

Kopiert die enthaltenen Daten in einen anderen [StreamContainer](/psd/python-net/aspose.psd/streamcontainer/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Container, in den kopiert werden soll. |
| Länge | long | Die Anzahl der zu schreibenden Bytes. |

