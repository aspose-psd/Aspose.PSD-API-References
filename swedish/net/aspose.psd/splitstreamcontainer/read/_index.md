---
title: SplitStreamContainer.Read
second_title: Aspose.PSD för .NET API-referens
description: SplitStreamContainer metod. Läser bytes för att fylla den angivna bytebufferten.
type: docs
weight: 110
url: /sv/net/aspose.psd/splitstreamcontainer/read/
---
## Read(byte[]) {#read}

Läser bytes för att fylla den angivna bytebufferten.

```csharp
public override int Read(byte[] bytes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | Byte[] | Byte som ska fyllas. |

### Returvärde

Antalet lästa byte. Detta värde kan vara mindre än antalet byte i bufferten om det inte finns tillräckligt med byte i strömmen.

### Se även

* class [SplitStreamContainer](../)
* namnutrymme [Aspose.PSD](../../splitstreamcontainer/)
* hopsättning [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

Läser en sekvens av byte från den aktuella strömmen och flyttar fram positionen i strömmen med antalet lästa byte.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | Byte[] | En uppsättning byte. När den här metoden returnerar, innehåller bufferten den angivna byte-arrayen med värdena mellan*offset* och (*offset* +*count* - 1) ersätts av byten som läses från den aktuella källan. |
| offset | Int32 | Den nollbaserade byteoffset in*buffer* där man ska börja lagra data som läses från den aktuella strömmen. |
| count | Int32 | Det maximala antalet byte som ska läsas från den aktuella strömmen. |

### Returvärde

Det totala antalet byte som läses in i bufferten. Detta kan vara mindre än antalet begärda byte om så många byte inte är tillgängliga för närvarande, eller noll (0) om slutet av strömmen har nåtts.

### Se även

* class [SplitStreamContainer](../)
* namnutrymme [Aspose.PSD](../../splitstreamcontainer/)
* hopsättning [Aspose.PSD](../../../)


