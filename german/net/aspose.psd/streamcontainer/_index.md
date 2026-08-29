---
title: "Klasse StreamContainer"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.StreamContainer‑Klasse. Stellt einen Stream‑Container dar, der den Stream enthält und Routinen zur Stream‑Verarbeitung bereitstellt"
type: docs
weight: 6140
url: /de/net/aspose.psd/streamcontainer/
---
{{< psd/tize >}}
## StreamContainer class

Stellt einen Stream-Container dar, der den Stream enthält und Stream-Verarbeitungsroutinen bereitstellt.

```csharp
public class StreamContainer : DisposableObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | Initialisiert eine neue Instanz der Klasse `StreamContainer`. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | Initialisiert eine neue Instanz der Klasse `StreamContainer`. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Gibt einen Wert zurück, der angibt, ob der Stream das Lesen unterstützt. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Gibt einen Wert zurück, der angibt, ob der Stream das Suchen unterstützt. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Gibt einen Wert zurück, der angibt, ob der Stream das Schreiben unterstützt. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Gibt einen Wert zurück, der angibt, ob dieser Stream beim Schließen freigegeben wird. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Liest oder setzt die Stream-Länge in Bytes. Dieser Wert ist kleiner als die Länge um die Startposition des Streams, die im Konstruktor von StreamContainer übergeben wurde. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Liest oder setzt die aktuelle Position im Stream. Dieser Wert stellt den Versatz von der Startposition des Streams dar, die im Konstruktor von StreamContainer übergeben wurde. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Liest den Datenstream. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Liest ein Objekt, das zur Synchronisation des Zugriffs auf die synchronisierte Ressource verwendet werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Leert alle Puffer für diesen Stream und bewirkt, dass gepufferte Daten in das zugrunde liegende Gerät geschrieben werden. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | Liest Bytes, um den angegebenen Byte-Puffer zu füllen. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | Liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die Anzahl der gelesenen Bytes. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard‑Puffergröße [`ReadWriteBytesCount`](./readwritebytescount/) und den Stream‑Wert [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard‑Puffergröße [`ReadWriteBytesCount`](./readwritebytescount/) und den Stream‑Wert [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet den Stream‑Wert [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet den Stream‑Wert [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Setzt die Position im aktuellen Stream. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Setzt die Stream-Position auf den Anfang des Streams. Dieser Wert stellt den Versatz von der Startposition des Streams dar, die im Konstruktor von StreamContainer übergeben wurde. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | Konvertiert die Stream-Daten in das Byte-Array. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | Konvertiert die Stream-Daten in das Byte-Array. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | Schreibt alle angegebenen Bytes in den Stream. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | Schreibt eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Schreibt ein Byte an die aktuelle Position im Stream und verschiebt die Position im Stream um ein Byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | Kopiert die enthaltenen Daten in einen anderen `StreamContainer`. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | Kopiert die enthaltenen Daten in einen anderen `StreamContainer`. |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | Führt eine explizite Konvertierung von `StreamContainer` zu Stream durch. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | Gibt die Anzahl der Lese‑ und Schreib‑Bytes beim sequentiellen Lesen an. |

### Siehe auch

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


