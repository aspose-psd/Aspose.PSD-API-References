---
title: Class StreamContainer
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.StreamContainer klass. Representerar strömbehållare som innehåller strömmen och tillhandahåller strömbehandlingsrutiner.
type: docs
weight: 5640
url: /sv/net/aspose.psd/streamcontainer/
---
## StreamContainer class

Representerar strömbehållare som innehåller strömmen och tillhandahåller strömbehandlingsrutiner.

```csharp
public class StreamContainer : DisposableObject
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | Initierar en ny instans av`StreamContainer` class. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | Initierar en ny instans av`StreamContainer` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Får ett värde som anger om strömmen stöder läsning. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Får ett värde som indikerar om ström stöder sökning. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Får ett värde som indikerar om ström stöder skrivning. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Får ett värde som indikerar om den här strömmen slängs vid stängning. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Hämtar eller ställer in strömlängden i byte. Detta värde är mindre änLengthav startströmpositionen som skickas i StreamContainer-konstruktorn. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Hämtar eller ställer in den aktuella positionen i strömmen. Detta värde representerar offset från startströmpositionen som skickats i StreamContainer-konstruktorn. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Hämtar dataströmmen. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Tar bort den aktuella instansen. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Rensar alla buffertar för denna ström och gör att all buffrad data skrivs till den underliggande enheten. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | Läser bytes för att fylla den angivna bytebufferten. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | Läser en sekvens av byte från den aktuella strömmen och flyttar fram positionen i strömmen med antalet lästa byte. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Läser en byte från strömmen och flyttar fram positionen i strömmen med en byte, eller returnerar -1 om i slutet av strömmen. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek[`ReadWriteBytesCount`](./readwritebytescount/) och strömma[`Length`](./length/) värde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek[`ReadWriteBytesCount`](./readwritebytescount/) och strömma[`Length`](./length/) värde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | Sparar (kopierar) all ströms data till den angivna strömmen. Använder stream[`Length`](./length/) värde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder stream[`Length`](./length/) värde. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Ställer in positionen inom den aktuella strömmen. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Ställer in strömningspositionen till början av strömmen. Detta värde representerar offset från startströmpositionen som skickats i StreamContainer-konstruktorn. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | Konverterar strömdata tillByte array. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | Konverterar strömdata tillByte array. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | Skriver alla angivna byte till strömmen. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | Skriver en sekvens av byte till den aktuella strömmen och flyttar fram den aktuella positionen inom denna ström med antalet skrivna byte. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Skriver en byte till den aktuella positionen i strömmen och flyttar fram positionen i strömmen med en byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | Kopierar ingående data till en annan`StreamContainer` . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | Kopierar ingående data till en annan`StreamContainer` . |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | Utför en explicit konvertering från`StreamContainer` tillStream . |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | Anger antal läs- och skrivbytes vid sekventiell läsning. |

### Se även

* class [DisposableObject](../disposableobject/)
* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


