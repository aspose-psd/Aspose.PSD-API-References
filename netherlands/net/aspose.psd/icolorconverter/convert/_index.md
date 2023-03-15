---
title: IColorConverter.Convert
second_title: Aspose.PSD voor .NET API-referentie
description: IColorConverter methode. Converteert de doorgegeven gegevens naar het uitvoerformaat.
type: docs
weight: 10
url: /nl/net/aspose.psd/icolorconverter/convert/
---
## IColorConverter.Convert method

Converteert de doorgegeven gegevens naar het uitvoerformaat.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | Het bronformaat. |
| data | Byte[] | De brongegevens. |
| offset | Int32 | De offset in bytes waar het kopiëren van gegevens moet beginnen. |
| bitStart | Int32 | Het begin van het bit. Merk op dat deze waarde geen byte-uitgelijnde waarde is, maar dat dit de werkelijke bit is waar het kopiëren moet beginnen. |
| samplesCount | Int32 | De monsters tellen. |
| linesCount | Int32 | De lijnen tellen. |
| destFormat | PixelDataFormat | Het bestemmingsformaat. |
| outputData | Byte[] | De uitvoergegevens. |
| outputOffset | Int32 | De uitvoeroffset waar het kopiëren van gegevens moet beginnen. |

### Winstwaarde

Het aantal geconverteerde bytes.

### Zie ook

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* naamruimte [Aspose.PSD](../../icolorconverter/)
* montage [Aspose.PSD](../../../)


