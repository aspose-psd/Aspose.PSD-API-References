---
title: "Klass SplitStreamContainer"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.SplitStreamContainer-klass. Representerar en delad strömkontainer som innehåller strömmen och tillhandahåller rutiner för strömbehandling."
type: docs
weight: 6130
url: /sv/net/aspose.psd/splitstreamcontainer/
---
{{< psd/tize >}}
## SplitStreamContainer class

Representerar en delad strömkontainer som innehåller strömmen och tillhandahåller strömbehandlingsrutiner.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Initierar en ny instans av klassen `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Initierar en ny instans av klassen `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Initierar en ny instans av klassen `SplitStreamContainer`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Hämtar ett värde som indikerar om strömmen stödjer läsning. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Hämtar ett värde som indikerar om strömmen stödjer sökning. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Hämtar ett värde som indikerar om strömmen stödjer skrivning. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Hämtar ett värde som indikerar om denna ström avyttras vid stängning. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Hämtar eller anger strömlängden i byte. Detta värde är mindre än Length med startpositionen för strömmen som skickas till konstruktorn för StreamContainer. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Hämtar eller anger den aktuella positionen i strömmen. Detta värde representerar avståndet från startpositionen för strömmen som skickas till konstruktorn för StreamContainer. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Hämtar datastreamen. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Rensar alla buffertar för denna ström och får all buffrad data att skrivas till den underliggande enheten. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Infogar stream container på den angivna positionen. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Läser byte för att fylla den angivna bytebufferten. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Läser en sekvens av byte från den aktuella strömmen och förflyttar positionen i strömmen med antalet lästa byte. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Läser ett byte från strömmen och förflyttar positionen i strömmen med ett byte, eller returnerar -1 om man är i slutet av strömmen. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) och strömvärdet [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) och strömvärdet [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Sparar (kopierar) all data från strömmen till den angivna strömmen. Använder strömvärdet [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder strömvärdet [`Length`](../streamcontainer/length/). |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Anger positionen i den aktuella strömmen. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Anger strömmens position till början av strömmen. Detta värde representerar avståndet från startpositionen för strömmen som skickas till konstruktorn för StreamContainer. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Konverterar strömmens data till en Byte-array. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Konverterar strömmens data till en Byte-array. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Skriver alla angivna byte till strömmen. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Skriver en sekvens av byte till den aktuella strömmen och förflyttar den aktuella positionen i denna ström med antalet skrivna byte. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Skriver ett byte till den aktuella positionen i strömmen och förflyttar positionen i strömmen med ett byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Kopierar den innehållande datan till en annan [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Kopierar den innehållande datan till en annan [`StreamContainer`](../streamcontainer/). |

### Se även

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


