---
title: Class StreamContainer
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.StreamContainer klas. Vertegenwoordigt de stroomcontainer die de stroom bevat en stroomverwerkingsroutines biedt.
type: docs
weight: 5640
url: /nl/net/aspose.psd/streamcontainer/
---
## StreamContainer class

Vertegenwoordigt de stroomcontainer die de stroom bevat en stroomverwerkingsroutines biedt.

```csharp
public class StreamContainer : DisposableObject
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | Initialiseert een nieuw exemplaar van het`StreamContainer` klasse. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | Initialiseert een nieuw exemplaar van het`StreamContainer` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Krijgt een waarde die aangeeft of stream lezen ondersteunt. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Krijgt een waarde die aangeeft of stream zoeken ondersteunt. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Krijgt een waarde die aangeeft of stream schrijven ondersteunt. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Krijgt een waarde die aangeeft of deze stream wordt verwijderd bij sluiten. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Haalt of stelt de streamlengte in bytes in. Deze waarde is lager dan deLengthdoor de beginstroompositie doorgegeven in de StreamContainer-constructor. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Haalt of stelt de huidige positie binnen de stream in. Deze waarde vertegenwoordigt de afwijking van de startpositie van de stream die is doorgegeven in de StreamContainer-constructor. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Haalt de gegevensstroom op. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Haalt een object op dat kan worden gebruikt om de toegang tot de gesynchroniseerde bron te synchroniseren. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Wist alle buffers voor deze stream en zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | Leest bytes om de gespecificeerde bytesbuffer te vullen. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | Leest een reeks bytes uit de huidige stream en verhoogt de positie binnen de stream met het aantal gelezen bytes. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Leest een byte uit de stream en verschuift de positie binnen de stream met één byte, of retourneert -1 indien aan het einde van de stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | Slaat (kopieert) de data van de stream op naar de gespecificeerde stream. Gebruikt standaard buffergrootte[`ReadWriteBytesCount`](./readwritebytescount/) en stroom[`Length`](./length/) waarde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | Slaat (kopieert) de data van de stream op naar de gespecificeerde stream. Gebruikt standaard buffergrootte[`ReadWriteBytesCount`](./readwritebytescount/) en stroom[`Length`](./length/) waarde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | Bewaart (kopieert) alle data van de stream naar de gespecificeerde stream. Gebruikt stroom[`Length`](./length/) waarde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | Slaat (kopieert) de data van de stream op naar de gespecificeerde stream. Gebruikt stroom[`Length`](./length/) waarde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | Bewaart (kopieert) de data van de stream naar de gespecificeerde stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | Bewaart (kopieert) de data van de stream naar de gespecificeerde stream. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Stelt de positie binnen de huidige stream in. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Stelt de streampositie in op het begin van de stream. Deze waarde vertegenwoordigt de afwijking van de startpositie van de stream die is doorgegeven in de StreamContainer-constructor. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | Converteert de streamgegevens naar deByte matrix. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | Converteert de streamgegevens naar deByte matrix. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | Schrijft alle gespecificeerde bytes naar de stream. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | Schrijft een reeks bytes naar de huidige stream en verhoogt de huidige positie binnen deze stream met het aantal geschreven bytes. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Schrijft een byte naar de huidige positie in de stream en verhoogt de positie binnen de stream met één byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | Kopieert de ingesloten gegevens naar een andere`StreamContainer` . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | Kopieert de ingesloten gegevens naar een andere`StreamContainer` . |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | Voert een expliciete conversie uit van`StreamContainer` naarStream . |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | Specificeert het aantal lees- en schrijfbytes bij sequentieel lezen. |

### Zie ook

* class [DisposableObject](../disposableobject/)
* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


