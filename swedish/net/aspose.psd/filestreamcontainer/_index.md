---
title: Class FileStreamContainer
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileStreamContainer klass. Hjälpare för bearbetning av filström.
type: docs
weight: 4250
url: /sv/net/aspose.psd/filestreamcontainer/
---
## FileStreamContainer class

Hjälpare för bearbetning av filström.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Får ett värde som anger om strömmen stöder läsning. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Får ett värde som indikerar om ström stöder sökning. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Får ett värde som indikerar om ström stöder skrivning. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | Hämtar filsökvägen. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | Får ett värde som anger om strömmen skapades explicit. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Får ett värde som indikerar om den här strömmen slängs vid stängning. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | Hämtar eller ställer in ett värde som anger om strömmen är temporär. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Hämtar eller ställer in strömlängden i byte. Detta värde är mindre änLengthav startströmpositionen som skickas i StreamContainer-konstruktorn. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Hämtar eller ställer in den aktuella positionen i strömmen. Detta värde representerar offset från startströmpositionen som skickats i StreamContainer-konstruktorn. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Hämtar dataströmmen. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | Skapar en ny filström. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | Öppnar en befintlig filström. Om filströmmen inte finns skapas lämpligt undantag. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Rensar alla buffertar för denna ström och gör att all buffrad data skrivs till den underliggande enheten. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | Läser bytes för att fylla den angivna bytebufferten. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | Läser en sekvens av byte från den aktuella strömmen och flyttar fram positionen i strömmen med antalet lästa byte. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Läser en byte från strömmen och flyttar fram positionen i strömmen med en byte, eller returnerar -1 om i slutet av strömmen. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) och strömma[`Length`](../streamcontainer/length/) värde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) och strömma[`Length`](../streamcontainer/length/) värde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Sparar (kopierar) all ströms data till den angivna strömmen. Använder stream[`Length`](../streamcontainer/length/) värde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder stream[`Length`](../streamcontainer/length/) värde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Ställer in positionen inom den aktuella strömmen. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Ställer in strömningspositionen till början av strömmen. Detta värde representerar offset från startströmpositionen som skickats i StreamContainer-konstruktorn. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | Konverterar strömdata tillByte array. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | Konverterar strömdata tillByte array. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | Skriver alla angivna byte till strömmen. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | Skriver en sekvens av byte till den aktuella strömmen och flyttar fram den aktuella positionen inom denna ström med antalet skrivna byte. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Skriver en byte till den aktuella positionen i strömmen och flyttar fram positionen i strömmen med en byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Kopierar ingående data till en annan[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Kopierar ingående data till en annan[`StreamContainer`](../streamcontainer/) . |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | Utför en explicit konvertering från`FileStreamContainer` tillStream . (2 operators) |

### Se även

* class [StreamContainer](../streamcontainer/)
* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


