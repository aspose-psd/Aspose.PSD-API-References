---
title: Class SplitStreamContainer
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.SplitStreamContainer klass. Representerar delad strömbehållare som innehåller strömmen och tillhandahåller strömbehandlingsrutiner.
type: docs
weight: 5630
url: /sv/net/aspose.psd/splitstreamcontainer/
---
## SplitStreamContainer class

Representerar delad strömbehållare som innehåller strömmen och tillhandahåller strömbehandlingsrutiner.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Initierar en ny instans av`SplitStreamContainer` class. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Initierar en ny instans av`SplitStreamContainer` class. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Initierar en ny instans av`SplitStreamContainer` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Får ett värde som anger om strömmen stöder läsning. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Får ett värde som indikerar om ström stöder sökning. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Får ett värde som indikerar om ström stöder skrivning. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Får ett värde som indikerar om den här strömmen slängs vid stängning. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Hämtar eller ställer in strömlängden i byte. Detta värde är mindre änLengthav startströmpositionen som skickas i StreamContainer-konstruktorn. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Hämtar eller ställer in den aktuella positionen i strömmen. Detta värde representerar offset från startströmpositionen som skickats i StreamContainer-konstruktorn. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Hämtar dataströmmen. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Rensar alla buffertar för denna ström och gör att all buffrad data skrivs till den underliggande enheten. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Infogar strömbehållaren i angiven position. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Läser bytes för att fylla den angivna bytebufferten. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Läser en sekvens av byte från den aktuella strömmen och flyttar fram positionen i strömmen med antalet lästa byte. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Läser en byte från strömmen och flyttar fram positionen i strömmen med en byte, eller returnerar -1 om i slutet av strömmen. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) och strömma[`Length`](../streamcontainer/length/) värde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) och strömma[`Length`](../streamcontainer/length/) värde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Sparar (kopierar) all ströms data till den angivna strömmen. Använder stream[`Length`](../streamcontainer/length/) värde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder stream[`Length`](../streamcontainer/length/) värde. |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Ställer in positionen inom den aktuella strömmen. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Ställer in strömningspositionen till början av strömmen. Detta värde representerar offset från startströmpositionen som skickats i StreamContainer-konstruktorn. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Konverterar strömdata tillByte array. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Konverterar strömdata tillByte array. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Skriver alla angivna byte till strömmen. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Skriver en sekvens av byte till den aktuella strömmen och flyttar fram den aktuella positionen inom denna ström med antalet skrivna byte. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Skriver en byte till den aktuella positionen i strömmen och flyttar fram positionen i strömmen med en byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Kopierar ingående data till en annan[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Kopierar ingående data till en annan[`StreamContainer`](../streamcontainer/) . |

### Se även

* class [StreamContainer](../streamcontainer/)
* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


