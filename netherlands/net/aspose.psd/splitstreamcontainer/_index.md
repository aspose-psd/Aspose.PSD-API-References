---
title: Class SplitStreamContainer
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.SplitStreamContainer klas. Vertegenwoordigt gesplitste stroomcontainer die de stroom bevat en stroomverwerkingsroutines biedt.
type: docs
weight: 5630
url: /nl/net/aspose.psd/splitstreamcontainer/
---
## SplitStreamContainer class

Vertegenwoordigt gesplitste stroomcontainer die de stroom bevat en stroomverwerkingsroutines biedt.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Initialiseert een nieuw exemplaar van het`SplitStreamContainer` klasse. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Initialiseert een nieuw exemplaar van het`SplitStreamContainer` klasse. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Initialiseert een nieuw exemplaar van het`SplitStreamContainer` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Krijgt een waarde die aangeeft of stream lezen ondersteunt. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Krijgt een waarde die aangeeft of stream zoeken ondersteunt. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Krijgt een waarde die aangeeft of stream schrijven ondersteunt. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Krijgt een waarde die aangeeft of deze instantie is verwijderd. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Krijgt een waarde die aangeeft of deze stream wordt verwijderd bij sluiten. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Haalt of stelt de streamlengte in bytes in. Deze waarde is lager dan deLengthdoor de beginstroompositie doorgegeven in de StreamContainer-constructor. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Haalt of stelt de huidige positie binnen de stream in. Deze waarde vertegenwoordigt de afwijking van de startpositie van de stream die is doorgegeven in de StreamContainer-constructor. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Haalt de gegevensstroom op. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Haalt een object op dat kan worden gebruikt om de toegang tot de gesynchroniseerde bron te synchroniseren. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Verwijdert de huidige instantie. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Wist alle buffers voor deze stream en zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Voegt de streamcontainer in de gespecificeerde positie in. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Leest bytes om de gespecificeerde bytesbuffer te vullen. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Leest een reeks bytes uit de huidige stream en verhoogt de positie binnen de stream met het aantal gelezen bytes. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Leest een byte uit de stream en verschuift de positie binnen de stream met één byte, of retourneert -1 indien aan het einde van de stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Slaat (kopieert) de data van de stream op naar de gespecificeerde stream. Gebruikt standaard buffergrootte[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) en stroom[`Length`](../streamcontainer/length/) waarde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Slaat (kopieert) de data van de stream op naar de gespecificeerde stream. Gebruikt standaard buffergrootte[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) en stroom[`Length`](../streamcontainer/length/) waarde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Bewaart (kopieert) alle data van de stream naar de gespecificeerde stream. Gebruikt stroom[`Length`](../streamcontainer/length/) waarde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Slaat (kopieert) de data van de stream op naar de gespecificeerde stream. Gebruikt stroom[`Length`](../streamcontainer/length/) waarde. |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Bewaart (kopieert) de data van de stream naar de gespecificeerde stream. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Bewaart (kopieert) de data van de stream naar de gespecificeerde stream. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Stelt de positie binnen de huidige stream in. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Stelt de streampositie in op het begin van de stream. Deze waarde vertegenwoordigt de afwijking van de startpositie van de stream die is doorgegeven in de StreamContainer-constructor. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Converteert de streamgegevens naar deByte matrix. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Converteert de streamgegevens naar deByte matrix. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Schrijft alle gespecificeerde bytes naar de stream. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Schrijft een reeks bytes naar de huidige stream en verhoogt de huidige positie binnen deze stream met het aantal geschreven bytes. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Schrijft een byte naar de huidige positie in de stream en verhoogt de positie binnen de stream met één byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Kopieert de ingesloten gegevens naar een andere[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Kopieert de ingesloten gegevens naar een andere[`StreamContainer`](../streamcontainer/) . |

### Zie ook

* class [StreamContainer](../streamcontainer/)
* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


