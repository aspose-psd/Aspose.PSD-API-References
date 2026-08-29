---
title: "Klass StreamContainer"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.StreamContainer-klass. Representerar strömbehållare som innehåller strömmen och tillhandahåller strömbehandlingsrutiner."
type: docs
weight: 6140
url: /sv/net/aspose.psd/streamcontainer/
---
{{< psd/tize >}}
## StreamContainer class

Representerar en strömkontainer som innehåller strömmen och tillhandahåller strömbehandlingsrutiner.

```csharp
public class StreamContainer : DisposableObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | Initierar en ny instans av klassen `StreamContainer`. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | Initierar en ny instans av klassen `StreamContainer`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Hämtar ett värde som indikerar om strömmen stödjer läsning. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Hämtar ett värde som indikerar om strömmen stödjer sökning. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Hämtar ett värde som indikerar om strömmen stödjer skrivning. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Hämtar ett värde som indikerar om denna instans har frigjorts. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Hämtar ett värde som indikerar om denna ström avyttras vid stängning. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Hämtar eller anger strömlängden i byte. Detta värde är mindre än Length med startpositionen för strömmen som skickas till konstruktorn för StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Hämtar eller anger den aktuella positionen i strömmen. Detta värde representerar avståndet från startpositionen för strömmen som skickas till konstruktorn för StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Hämtar datastreamen. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till den synkroniserade resursen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Frigör den aktuella instansen. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Rensar alla buffertar för denna ström och får all buffrad data att skrivas till den underliggande enheten. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | Läser byte för att fylla den angivna bytebufferten. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | Läser en sekvens av byte från den aktuella strömmen och förflyttar positionen i strömmen med antalet lästa byte. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Läser ett byte från strömmen och förflyttar positionen i strömmen med ett byte, eller returnerar -1 om man är i slutet av strömmen. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [`ReadWriteBytesCount`](./readwritebytescount/) och strömvärdet [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder standardbuffertstorlek [`ReadWriteBytesCount`](./readwritebytescount/) och strömvärdet [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | Sparar (kopierar) all strömmens data till den angivna strömmen. Använder strömvärdet [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | Sparar (kopierar) strömmens data till den angivna strömmen. Använder strömvärdet [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | Sparar (kopierar) strömmens data till den angivna strömmen. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Anger positionen i den aktuella strömmen. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Anger strömmens position till början av strömmen. Detta värde representerar avståndet från startpositionen för strömmen som skickas till konstruktorn för StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | Konverterar strömmens data till en Byte-array. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | Konverterar strömmens data till en Byte-array. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | Skriver alla angivna byte till strömmen. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | Skriver en sekvens av byte till den aktuella strömmen och förflyttar den aktuella positionen i denna ström med antalet skrivna byte. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Skriver ett byte till den aktuella positionen i strömmen och förflyttar positionen i strömmen med ett byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | Kopierar det innehållande data till en annan `StreamContainer`. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | Kopierar det innehållande data till en annan `StreamContainer`. |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | Utför en explicit konvertering från `StreamContainer` till Stream. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | Anger antal läs- och skrivbyte vid sekventiell läsning. |

### Se även

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


