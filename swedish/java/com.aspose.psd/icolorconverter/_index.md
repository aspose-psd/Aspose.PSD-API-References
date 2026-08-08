---
title: "IColorConverter"
second_title: "Aspose.PSD för Java API-referens"
description: "Färgkonverteraren."
type: docs
weight: 116
url: /sv/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

Färgkonverteraren.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | Konverterar den överförda datan till utdataformatet. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


Konverterar den överförda datan till utdataformatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Källformatet. |
| data | byte[] | Källdata. |
| offset | int | Offseten i byte där datakopiering ska börja. |
| bitStart | int | Bitstarten. Observera att detta värde inte är bytejusterat utan är den faktiska biten där kopieringen ska börja. |
| samplesCount | int | Antalet prover. |
| linesCount | int | Antalet rader. |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Målformatet. |
| outputData | byte[] | Utdatan. |
| outputOffset | int | Utdatoffseten där datakopiering ska starta. |

**Returns:**
int - Antalet konverterade byte.
