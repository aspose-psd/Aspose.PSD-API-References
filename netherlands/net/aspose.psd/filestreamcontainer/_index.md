---
title: Class FileStreamContainer
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileStreamContainer klas. Helper voor verwerking van bestandsstromen.
type: docs
weight: 4250
url: /nl/net/aspose.psd/filestreamcontainer/
---
## FileStreamContainer class

Helper voor verwerking van bestandsstromen.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Krijgt een waarde die aangeeft of stream lezen ondersteunt. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Krijgt een waarde die aangeeft of stream zoeken ondersteunt. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Krijgt een waarde die aangeeft of stream schrijven ondersteunt. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | Haalt het bestandspad op. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | Krijgt een waarde die aangeeft of de stream expliciet is gemaakt. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Krijgt een waarde die aangeeft of deze stream wordt verwijderd bij sluiten. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | Haalt of stelt een waarde in die aangeeft of stream tijdelijk is. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Haalt of stelt de streamlengte in bytes in. Deze waarde is lager dan deLengthdoor de beginstroompositie doorgegeven in de StreamContainer-constructor. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Haalt of stelt de huidige positie binnen de stream in. Deze waarde vertegenwoordigt de afwijking van de startpositie van de stream die is doorgegeven in de StreamContainer-constructor. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Haalt de gegevensstroom op. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Haalt een object op dat kan worden gebruikt om de toegang tot de gesynchroniseerde bron te synchroniseren. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | Creëert een nieuwe bestandsstroom. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | Opent een bestaande bestandsstroom. Als de bestandsstroom niet bestaat, wordt de juiste uitzondering gegenereerd. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Wist alle buffers voor deze stream en zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | Leest bytes om de gespecificeerde bytesbuffer te vullen. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | Leest een reeks bytes uit de huidige stream en verhoogt de positie binnen de stream met het aantal gelezen bytes. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Leest een byte uit de stream en verschuift de positie binnen de stream met één byte, of retourneert -1 indien aan het einde van de stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Slaat (kopieert) de data van de stream op naar de gespecificeerde stream. Gebruikt standaard buffergrootte[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) en stroom[`Length`](../streamcontainer/length/) waarde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Slaat (kopieert) de data van de stream op naar de gespecificeerde stream. Gebruikt standaard buffergrootte[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) en stroom[`Length`](../streamcontainer/length/) waarde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Bewaart (kopieert) alle data van de stream naar de gespecificeerde stream. Gebruikt stroom[`Length`](../streamcontainer/length/) waarde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Slaat (kopieert) de data van de stream op naar de gespecificeerde stream. Gebruikt stroom[`Length`](../streamcontainer/length/) waarde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | Bewaart (kopieert) de data van de stream naar de gespecificeerde stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Bewaart (kopieert) de data van de stream naar de gespecificeerde stream. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Stelt de positie binnen de huidige stream in. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Stelt de streampositie in op het begin van de stream. Deze waarde vertegenwoordigt de afwijking van de startpositie van de stream die is doorgegeven in de StreamContainer-constructor. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | Converteert de streamgegevens naar deByte matrix. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | Converteert de streamgegevens naar deByte matrix. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | Schrijft alle gespecificeerde bytes naar de stream. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | Schrijft een reeks bytes naar de huidige stream en verhoogt de huidige positie binnen deze stream met het aantal geschreven bytes. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Schrijft een byte naar de huidige positie in de stream en verhoogt de positie binnen de stream met één byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Kopieert de ingesloten gegevens naar een andere[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Kopieert de ingesloten gegevens naar een andere[`StreamContainer`](../streamcontainer/) . |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | Voert een expliciete conversie uit van`FileStreamContainer` naarStream . (2 operators) |

### Zie ook

* class [StreamContainer](../streamcontainer/)
* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


