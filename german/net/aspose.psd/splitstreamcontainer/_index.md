---
title: "Klasse SplitStreamContainer"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.SplitStreamContainer Klasse. Stellt einen geteilten Stream-Container dar, der den Stream enthält und Routinen zur Stream-Verarbeitung bereitstellt"
type: docs
weight: 6130
url: /de/net/aspose.psd/splitstreamcontainer/
---
{{< psd/tize >}}
## SplitStreamContainer class

Stellt einen geteilten Stream-Container dar, der den Stream enthält und Stream-Verarbeitungsroutinen bereitstellt.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Initialisiert eine neue Instanz der `SplitStreamContainer` Klasse. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Initialisiert eine neue Instanz der `SplitStreamContainer` Klasse. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Initialisiert eine neue Instanz der `SplitStreamContainer` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Gibt einen Wert zurück, der angibt, ob der Stream das Lesen unterstützt. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Gibt einen Wert zurück, der angibt, ob der Stream das Suchen unterstützt. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Gibt einen Wert zurück, der angibt, ob der Stream das Schreiben unterstützt. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Gibt einen Wert zurück, der angibt, ob dieser Stream beim Schließen freigegeben wird. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Liest oder setzt die Stream-Länge in Bytes. Dieser Wert ist kleiner als die Länge um die Startposition des Streams, die im Konstruktor von StreamContainer übergeben wurde. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Liest oder setzt die aktuelle Position im Stream. Dieser Wert stellt den Versatz von der Startposition des Streams dar, die im Konstruktor von StreamContainer übergeben wurde. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Liest den Datenstream. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Liest ein Objekt, das zur Synchronisation des Zugriffs auf die synchronisierte Ressource verwendet werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Leert alle Puffer für diesen Stream und bewirkt, dass gepufferte Daten in das zugrunde liegende Gerät geschrieben werden. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Fügt den Stream-Container an der angegebenen Position ein. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Liest Bytes, um den angegebenen Byte-Puffer zu füllen. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die Anzahl der gelesenen Bytes. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) und den Stream-[`Length`](../streamcontainer/length/) Wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) und den Stream-[`Length`](../streamcontainer/length/) Wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet den Stream-[`Length`](../streamcontainer/length/) Wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet den Stream-[`Length`](../streamcontainer/length/) Wert. |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Setzt die Position im aktuellen Stream. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Setzt die Stream-Position auf den Anfang des Streams. Dieser Wert stellt den Versatz von der Startposition des Streams dar, die im Konstruktor von StreamContainer übergeben wurde. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Konvertiert die Stream-Daten in das Byte-Array. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Konvertiert die Stream-Daten in das Byte-Array. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Schreibt alle angegebenen Bytes in den Stream. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Schreibt eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Schreibt ein Byte an die aktuelle Position im Stream und verschiebt die Position im Stream um ein Byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Kopiert die enthaltenen Daten in einen anderen [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Kopiert die enthaltenen Daten in einen anderen [`StreamContainer`](../streamcontainer/). |

### Siehe auch

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


