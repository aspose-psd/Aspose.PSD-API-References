---
title: "IColorConverter"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De kleurconverter."
type: docs
weight: 116
url: /nl/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

De kleurconverter.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | Converteert de doorgegeven gegevens naar het uitvoerformaat. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


Converteert de doorgegeven gegevens naar het uitvoerformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Het bronformaat. |
| gegevens | byte[] | De brongegevens. |
| offset | int | De offset in bytes waar het kopiëren van gegevens moet beginnen. |
| bitStart | int | De bitstart. Merk op dat deze waarde niet byte-uitgelijnd is, maar de feitelijke bit waar het kopiëren moet beginnen. |
| samplesCount | int | Het aantal monsters. |
| linesCount | int | Het aantal regels. |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Het bestemmingsformaat. |
| outputData | byte[] | De uitvoergegevens. |
| outputOffset | int | De uitvoeroffset waar het kopiëren van gegevens moet beginnen. |

**Returns:**
int - Het aantal geconverteerde bytes.
