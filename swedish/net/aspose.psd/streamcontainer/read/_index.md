---
title: "StreamContainer.Read"
second_title: "Aspose.PSD för .NET API‑referens"
description: "StreamContainer-metod. Läser byte för att fylla den angivna bytebufferten"
type: docs
weight: 110
url: /sv/net/aspose.psd/streamcontainer/read/
---
{{< psd/tize >}}
## Read(byte[]) {#read}

Läser byte för att fylla den angivna bytebufferten.

```csharp
public virtual int Read(byte[] bytes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | Byte[] | Byte att fylla. |

### Returvärde

Antalet lästa byte. Detta värde kan vara mindre än antalet byte i bufferten om det inte finns tillräckligt med byte i strömmen.

### Se även

* class [StreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Läser en sekvens av byte från den aktuella strömmen och förflyttar positionen i strömmen med antalet lästa byte.

```csharp
public virtual int Read(byte[] buffer, int offset, int count)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | Byte[] | En array av byte. När den här metoden returnerar innehåller bufferten den specificerade bytearrayen med värdena mellan *offset* och (*offset* + *count* - 1) ersatta av de byte som lästs från den aktuella källan. |
| offset | Int32 | Den nollbaserade byteoffseten i *buffer* där lagringen av data som lästs från den aktuella strömmen ska börja. |
| count | Int32 | Det maximala antalet byte som ska läsas från den aktuella strömmen. |

### Returvärde

Det totala antalet byte som lästs in i bufferten. Detta kan vara mindre än det begärda antalet byte om så många byte för närvarande inte är tillgängliga, eller noll (0) om slutet på strömmen har nåtts.

### Se även

* class [StreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


