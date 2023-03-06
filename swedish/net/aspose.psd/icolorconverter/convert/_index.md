---
title: IColorConverter.Convert
second_title: Aspose.PSD för .NET API-referens
description: IColorConverter metod. Konverterar överförd data till utdataformatet.
type: docs
weight: 10
url: /sv/net/aspose.psd/icolorconverter/convert/
---
## IColorConverter.Convert method

Konverterar överförd data till utdataformatet.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | Källformatet. |
| data | Byte[] | Källdata. |
| offset | Int32 | Offset i byte där datakopiering ska börja. |
| bitStart | Int32 | Biten börjar. Observera att detta värde inte är bytejusterat värde istället är detta den faktiska biten där kopieringen ska börja. |
| samplesCount | Int32 | Proverna räknas. |
| linesCount | Int32 | Raderna räknas. |
| destFormat | PixelDataFormat | Målformatet. |
| outputData | Byte[] | Utdata. |
| outputOffset | Int32 | Utgångsoffset där datakopiering ska börja. |

### Returvärde

Antalet konverterade byte.

### Se även

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namnutrymme [Aspose.PSD](../../icolorconverter/)
* hopsättning [Aspose.PSD](../../../)


