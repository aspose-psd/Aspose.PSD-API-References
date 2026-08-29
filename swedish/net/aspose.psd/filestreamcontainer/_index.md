---
title: "Klass FileStreamContainer"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileStreamContainer‑klass. Hjälpmedel för filströmshantering."
type: docs
weight: 4720
url: /sv/net/aspose.psd/filestreamcontainer/
---
{{< psd/tize >}}
## FileStreamContainer class

Hjälpmedel för filströmshantering.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Hämtar ett värde som indikerar om strömmen stödjer läsning. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Hämtar ett värde som indikerar om strömmen stödjer sökning. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Hämtar ett värde som indikerar om strömmen stödjer skrivning. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | Hämtar filsökvägen. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | Hämtar ett värde som indikerar om strömmen skapades explicit. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Hämtar ett värde som indikerar om denna ström avyttras vid stängning. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | Hämtar eller anger ett värde som indikerar om strömmen är temporär. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Hämtar eller anger strömlängden i byte. Detta värde är mindre än Length med startpositionen för strömmen som skickas till konstruktorn för StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Hämtar eller anger den aktuella positionen i strömmen. Detta värde representerar avståndet från startpositionen för strömmen som skickas till konstruktorn för StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Hämtar datastreamen. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | Skapar en ny filström. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | Öppnar en befintlig filström. Om filströmmen inte finns kastas lämpligt undantag. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Rensar alla buffertar för denna ström och får all buffrad data att skrivas till den underliggande enheten. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | Läser byte för att fylla den angivna bytebufferten. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | Läser en sekvens av byte från den aktuella strömmen och förflyttar positionen i strömmen med antalet lästa byte. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Läser ett byte från strömmen och förflyttar positionen i strömmen med ett byte, eller returnerar -1 om man är i slutet av strömmen. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) och strömvärdet [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) och strömvärdet [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Sparar (kopierar) all data från strömmen till den angivna strömmen. Använder strömvärdet [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder strömvärdet [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Anger positionen i den aktuella strömmen. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Anger strömmens position till början av strömmen. Detta värde representerar avståndet från startpositionen för strömmen som skickas till konstruktorn för StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | Konverterar strömmens data till en Byte-array. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | Konverterar strömmens data till en Byte-array. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | Skriver alla angivna byte till strömmen. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | Skriver en sekvens av byte till den aktuella strömmen och förflyttar den aktuella positionen i denna ström med antalet skrivna byte. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Skriver ett byte till den aktuella positionen i strömmen och förflyttar positionen i strömmen med ett byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Kopierar den innehållande datan till en annan [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Kopierar den innehållande datan till en annan [`StreamContainer`](../streamcontainer/). |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | Utför en explicit konvertering från `FileStreamContainer` till Stream. (2 operatorer) |

### Se även

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


