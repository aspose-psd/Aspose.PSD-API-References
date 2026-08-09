---
title: "Klasse FileStreamContainer"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileStreamContainer Klasse. Hilfsprogramm für die Verarbeitung von Dateistreams."
type: docs
weight: 4720
url: /de/net/aspose.psd/filestreamcontainer/
---
{{< psd/tize >}}
## FileStreamContainer class

Hilfsmittel für die Verarbeitung von Dateistreams.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Gibt einen Wert zurück, der angibt, ob der Stream das Lesen unterstützt. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Gibt einen Wert zurück, der angibt, ob der Stream das Suchen unterstützt. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Gibt einen Wert zurück, der angibt, ob der Stream das Schreiben unterstützt. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | Liefert den Dateipfad. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | Liefert einen Wert, der angibt, ob der Stream explizit erstellt wurde. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Gibt einen Wert zurück, der angibt, ob dieser Stream beim Schließen freigegeben wird. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | Liefert oder setzt einen Wert, der angibt, ob der Stream temporär ist. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Liest oder setzt die Stream-Länge in Bytes. Dieser Wert ist kleiner als die Länge um die Startposition des Streams, die im Konstruktor von StreamContainer übergeben wurde. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Liest oder setzt die aktuelle Position im Stream. Dieser Wert stellt den Versatz von der Startposition des Streams dar, die im Konstruktor von StreamContainer übergeben wurde. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Liest den Datenstream. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Liest ein Objekt, das zur Synchronisation des Zugriffs auf die synchronisierte Ressource verwendet werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | Erstellt einen neuen Dateistream. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | Öffnet einen bestehenden Dateistream. Wenn der Dateistream nicht existiert, wird die entsprechende Ausnahme ausgelöst. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Leert alle Puffer für diesen Stream und bewirkt, dass gepufferte Daten in das zugrunde liegende Gerät geschrieben werden. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | Liest Bytes, um den angegebenen Byte-Puffer zu füllen. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | Liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die Anzahl der gelesenen Bytes. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) und den Stream-[`Length`](../streamcontainer/length/) Wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standard-Puffergröße [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) und den Stream-[`Length`](../streamcontainer/length/) Wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet den Stream-[`Length`](../streamcontainer/length/) Wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet den Stream-[`Length`](../streamcontainer/length/) Wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Setzt die Position im aktuellen Stream. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Setzt die Stream-Position auf den Anfang des Streams. Dieser Wert stellt den Versatz von der Startposition des Streams dar, die im Konstruktor von StreamContainer übergeben wurde. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | Konvertiert die Stream-Daten in das Byte-Array. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | Konvertiert die Stream-Daten in das Byte-Array. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | Schreibt alle angegebenen Bytes in den Stream. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | Schreibt eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Schreibt ein Byte an die aktuelle Position im Stream und verschiebt die Position im Stream um ein Byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Kopiert die enthaltenen Daten in einen anderen [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Kopiert die enthaltenen Daten in einen anderen [`StreamContainer`](../streamcontainer/). |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | Führt eine explizite Konvertierung von `FileStreamContainer` zu Stream durch. (2 Operatoren) |

### Siehe auch

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


