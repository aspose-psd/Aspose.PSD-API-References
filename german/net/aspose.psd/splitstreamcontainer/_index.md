---
title: SplitStreamContainer
second_title: Aspose.PSD für .NET-API-Referenz
description: Repräsentiert SplitStreamContainer der den Stream enthält und StreamVerarbeitungsroutinen bereitstellt.
type: docs
weight: 5560
url: /de/net/aspose.psd/splitstreamcontainer/
---
## SplitStreamContainer class

Repräsentiert Split-Stream-Container, der den Stream enthält und Stream-Verarbeitungsroutinen bereitstellt.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer#constructor_1)(Stream) | Initialisiert eine neue Instanz von[`SplitStreamContainer`](../splitstreamcontainer) Klasse. |
| [SplitStreamContainer](splitstreamcontainer#constructor_2)(Stream, bool) | Initialisiert eine neue Instanz von[`SplitStreamContainer`](../splitstreamcontainer) Klasse. |
| [SplitStreamContainer](splitstreamcontainer#constructor)(StreamContainer, bool) | Initialisiert eine neue Instanz von[`SplitStreamContainer`](../splitstreamcontainer) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread) { get; } | Ruft einen Wert ab, der angibt, ob der Stream das Lesen unterstützt. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek) { get; } | Ruft einen Wert ab, der angibt, ob der Stream die Suche unterstützt. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite) { get; } | Ruft einen Wert ab, der angibt, ob der Stream das Schreiben unterstützt. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose) { get; } | Ruft einen Wert ab, der angibt, ob dieser Stream beim Schließen verworfen wird. |
| override [Length](../../aspose.psd/splitstreamcontainer/length) { get; set; } | Holt oder setzt die Streamlänge in Byte. Dieser Wert ist kleiner als dieLengthdurch die Start-Stream-Position, die im StreamContainer-Konstruktor übergeben wird. |
| override [Position](../../aspose.psd/splitstreamcontainer/position) { get; set; } | Holt oder setzt die aktuelle Position innerhalb des Streams. Dieser Wert stellt den Offset von der Start-Stream-Position dar, die im StreamContainer-Konstruktor übergeben wird. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream) { get; } | Ruft den Datenstrom ab. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot) { get; } | Ruft ein Objekt ab, das zum Synchronisieren des Zugriffs auf die synchronisierte Ressource verwendet werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush)() | Löscht alle Puffer für diesen Stream und bewirkt, dass alle gepufferten Daten auf das zugrunde liegende Gerät geschrieben werden. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert)(int, StreamContainer, bool) | Fügt den Stream-Container an der angegebenen Position ein. |
| override [Read](../../aspose.psd/splitstreamcontainer/read#read)(byte[]) | Liest Bytes, um den angegebenen Bytepuffer zu füllen. |
| override [Read](../../aspose.psd/splitstreamcontainer/read#read_1)(byte[], int, int) | Liest eine Folge von Bytes aus dem aktuellen Stream und erhöht die Position innerhalb des Streams um die Anzahl der gelesenen Bytes. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte)() | Liest ein Byte aus dem Stream und erhöht die Position innerhalb des Streams um ein Byte oder gibt -1 zurück, wenn am Ende des Streams. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(Stream) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standardpuffergröße[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) und streamen[`Length`](../streamcontainer/length) wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standardpuffergröße[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) und streamen[`Length`](../streamcontainer/length) wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(Stream, int) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet Stream[`Length`](../streamcontainer/length) wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string, int) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet Stream[`Length`](../streamcontainer/length) wert. |
| override [Save](../../aspose.psd/splitstreamcontainer/save#save_2)(Stream, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek)(long, SeekOrigin) | Legt die Position innerhalb des aktuellen Streams fest. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin)() | Setzt die Stream-Position auf den Beginn des Streams. Dieser Wert stellt den Offset von der Start-Stream-Position dar, die im StreamContainer-Konstruktor übergeben wird. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes#tobytes)() | Konvertiert die Stream-Daten in dieByte array. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes#tobytes_1)(long, long) | Konvertiert die Stream-Daten in dieByte array. |
| override [Write](../../aspose.psd/splitstreamcontainer/write#write)(byte[]) | Schreibt alle angegebenen Bytes in den Stream. |
| override [Write](../../aspose.psd/splitstreamcontainer/write#write_1)(byte[], int, int) | Schreibt eine Folge von Bytes in den aktuellen Stream und erhöht die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte)(byte) | Schreibt ein Byte an die aktuelle Position im Stream und erhöht die Position innerhalb des Streams um ein Byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto)(StreamContainer) | Kopiert die enthaltenen Daten in einen anderen[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto)(StreamContainer, long) | Kopiert die enthaltenen Daten in einen anderen[`StreamContainer`](../streamcontainer) . |

### Siehe auch

* class [StreamContainer](../streamcontainer)
* namensraum [Aspose.PSD](../../aspose.psd)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
