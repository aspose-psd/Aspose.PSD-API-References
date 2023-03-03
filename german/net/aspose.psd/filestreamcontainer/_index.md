---
title: Class FileStreamContainer
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileStreamContainer klas. Helfer für die Dateistreamverarbeitung.
type: docs
weight: 4250
url: /de/net/aspose.psd/filestreamcontainer/
---
## FileStreamContainer class

Helfer für die Dateistreamverarbeitung.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Ruft einen Wert ab, der angibt, ob der Stream das Lesen unterstützt. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Ruft einen Wert ab, der angibt, ob der Stream die Suche unterstützt. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Ruft einen Wert ab, der angibt, ob der Stream das Schreiben unterstützt. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | Ruft den Dateipfad ab. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | Ruft einen Wert ab, der angibt, ob der Stream explizit erstellt wurde. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Ruft einen Wert ab, der angibt, ob dieser Stream beim Schließen verworfen wird. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob der Stream zeitlich ist. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Holt oder setzt die Streamlänge in Byte. Dieser Wert ist kleiner als dieLengthdurch die Start-Stream-Position, die im StreamContainer-Konstruktor übergeben wird. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Holt oder setzt die aktuelle Position innerhalb des Streams. Dieser Wert stellt den Offset von der Start-Stream-Position dar, die im StreamContainer-Konstruktor übergeben wird. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Ruft den Datenstrom ab. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Ruft ein Objekt ab, das zum Synchronisieren des Zugriffs auf die synchronisierte Ressource verwendet werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | Erstellt einen neuen Dateistream. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | Öffnet einen bestehenden Dateistream. Wenn der Dateistream nicht existiert, wird die entsprechende Ausnahme ausgelöst. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwirft die aktuelle Instanz. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Löscht alle Puffer für diesen Stream und bewirkt, dass alle gepufferten Daten auf das zugrunde liegende Gerät geschrieben werden. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | Liest Bytes, um den angegebenen Bytepuffer zu füllen. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | Liest eine Folge von Bytes aus dem aktuellen Stream und erhöht die Position innerhalb des Streams um die Anzahl der gelesenen Bytes. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Liest ein Byte aus dem Stream und erhöht die Position innerhalb des Streams um ein Byte oder gibt -1 zurück, wenn am Ende des Streams. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standardpuffergröße[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) und streamen[`Length`](../streamcontainer/length/) wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet die Standardpuffergröße[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) und streamen[`Length`](../streamcontainer/length/) wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Speichert (kopiert) alle Daten des Streams in den angegebenen Stream. Verwendet Stream[`Length`](../streamcontainer/length/) wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. Verwendet Stream[`Length`](../streamcontainer/length/) wert. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Speichert (kopiert) die Daten des Streams in den angegebenen Stream. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Legt die Position innerhalb des aktuellen Streams fest. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Setzt die Stream-Position auf den Beginn des Streams. Dieser Wert stellt den Offset von der Start-Stream-Position dar, die im StreamContainer-Konstruktor übergeben wird. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | Konvertiert die Stream-Daten in dieByte array. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | Konvertiert die Stream-Daten in dieByte array. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | Schreibt alle angegebenen Bytes in den Stream. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | Schreibt eine Folge von Bytes in den aktuellen Stream und erhöht die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Schreibt ein Byte an die aktuelle Position im Stream und erhöht die Position innerhalb des Streams um ein Byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Kopiert die enthaltenen Daten in einen anderen[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Kopiert die enthaltenen Daten in einen anderen[`StreamContainer`](../streamcontainer/) . |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | Führt eine explizite Konvertierung von aus`FileStreamContainer` ZuStream . (2 operators) |

### Siehe auch

* class [StreamContainer](../streamcontainer/)
* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


