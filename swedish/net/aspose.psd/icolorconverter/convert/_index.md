---
title: "IColorConverter.Convert"
second_title: "Aspose.PSD för .NET API‑referens"
description: "IColorConverter metod. Konverterar den överförda datan till utdataformatet"
type: docs
weight: 10
url: /sv/net/aspose.psd/icolorconverter/convert/
---
{{< psd/tize >}}
## IColorConverter.Convert method

Konverterar den överförda datan till utdataformatet.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | Källformatet. |
| data | Byte[] | Källdata. |
| offset | Int32 | Förskjutningen i byte där datakopiering ska börja. |
| bitStart | Int32 | Bitstarten. Observera att detta värde inte är byte‑justerat utan är den faktiska biten där kopieringen ska börja. |
| samplesCount | Int32 | Antalet prover. |
| linesCount | Int32 | Antalet rader. |
| destFormat | PixelDataFormat | Destinationsformatet. |
| outputData | Byte[] | Utdata. |
| outputOffset | Int32 | Utdataförskjutningen där datakopiering ska börja. |

### Returvärde

Antalet konverterade byte.

### Se även

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


