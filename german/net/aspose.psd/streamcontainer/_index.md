---
title: StreamContainer
second_title: Aspose.PSD für .NET-API-Referenz
description: Stellt den StreamContainer dar der den Stream enthält und StreamVerarbeitungsroutinen bereitstellt.
type: docs
weight: 5570
url: /de/net/aspose.psd/streamcontainer/
---
## StreamContainer class

Stellt den Stream-Container dar, der den Stream enthält und Stream-Verarbeitungsroutinen bereitstellt.

```csharp
public class StreamContainer : DisposableObject
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [StreamContainer](streamcontainer#constructor)(Stream) | Initialisiert eine neue Instanz von[`StreamContainer`](../streamcontainer) Klasse. |
| [StreamContainer](streamcontainer#constructor_1)(Stream, bool) | Initialisiert eine neue Instanz von[`StreamContainer`](../streamcontainer) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread) { get; } | Ruft einen Wert ab, der angibt, ob der Stream das Lesen unterstützt. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek) { get; } | Ruft einen Wert ab, der angibt, ob der Stream die Suche unterstützt. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite) { get; } | Ruft einen Wert ab, der angibt, ob der Stream das Schreiben unterstützt. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose) { get; } | Ruft einen Wert ab, der angibt, ob dieser Stream beim Schließen verworfen wird. |
| virtual [Length](../../aspose.psd/streamcontainer/length) { get; set; } | Holt oder setzt die Streamlänge in Byte. Dieser Wert ist kleiner als dieLengthdurch die Start-Stream-Position, die im StreamContainer-Konstruktor übergeben wird. |
| virtual [Position](../../aspose.psd/streamcontainer/position) { get; set; } | Holt oder setzt die aktuelle Position innerhalb des Streams. Dieser Wert stellt den Offset von der Start-Stream-Position dar, die im StreamContainer-Konstruktor übergeben wird. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream) { get; } | Ruft den Datenstrom ab. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot) { get; } | Ruft ein Objekt ab, das zum Synchronisieren des Zugriffs auf die synchronisierte Ressource verwendet werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush)() | Löscht alle Puffer für diesen Stream und bewirkt, dass alle gepufferten Daten auf das zugrunde liegende Gerät geschrieben werden. |
| virtual [Read](../../aspose.psd/streamcontainer/read#read)(byte[]) | Liest Bytes, um den angegebenen Bytepuffer zu füllen. |
| virtual [Read](../../aspose.psd/streamcontainer/read#read_1)(byte[], int, int) | Liest eine Folge von Bytes aus dem aktuellen Stream und erhöht die Position innerhalb des Streams um die Anzahl der gelesenen Bytes. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte)() | Liest ein Byte aus dem Stream und erhöht die Position innerhalb des Streams um ein Byte oder gibt -1 zurück, wenn am Ende des Streams. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save)(Stream) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standardpuffergröße[`ReadWriteBytesCount`](./readwritebytescount) und streamen[`Length`](./length) wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_3)(string) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standardpuffergröße[`ReadWriteBytesCount`](./readwritebytescount) und streamen[`Length`](./length) wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_1)(Stream, int) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet Stream[`Length`](./length) wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_4)(string, int) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet Stream[`Length`](./length) wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_2)(Stream, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_5)(string, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek)(long, SeekOrigin) | Legt die Position innerhalb des aktuellen Streams fest. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin)() | Setzt die Stream-Position auf den Beginn des Streams. Dieser Wert stellt den Offset von der Start-Stream-Position dar, die im StreamContainer-Konstruktor übergeben wird. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes#tobytes)() | Konvertiert die Stream-Daten in dieByte array. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes#tobytes_1)(long, long) | Konvertiert die Stream-Daten in dieByte array. |
| virtual [Write](../../aspose.psd/streamcontainer/write#write)(byte[]) | Schreibt alle angegebenen Bytes in den Stream. |
| virtual [Write](../../aspose.psd/streamcontainer/write#write_1)(byte[], int, int) | Schreibt eine Folge von Bytes in den aktuellen Stream und erhöht die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte)(byte) | Schreibt ein Byte an die aktuelle Position im Stream und erhöht die Position innerhalb des Streams um ein Byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto#writeto)(StreamContainer) | Kopiert die enthaltenen Daten in einen anderen[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto#writeto_1)(StreamContainer, long) | Kopiert die enthaltenen Daten in einen anderen[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit) | Führt eine explizite Konvertierung von aus[`StreamContainer`](../streamcontainer) zuStream . |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount) | Gibt die Anzahl der Lese- und Schreibbytes beim sequenziellen Lesen an. |

### Siehe auch

* class [DisposableObject](../disposableobject)
* namensraum [Aspose.PSD](../../aspose.psd)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
