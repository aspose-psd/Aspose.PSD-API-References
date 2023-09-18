---
title: IColorConverter
second_title: Aspose.PSD for Java API Reference
description: The color converter.
type: docs
weight: 117
url: /java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

The color converter.
## Methods

| Method | Description |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | Converts the passed data to the output format. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


Converts the passed data to the output format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | The source format. |
| data | byte[] | The source data. |
| offset | int | The offset in bytes where data copying should begin. |
| bitStart | int | The bit start. Note this value is not byte aligned value instead this is actual bit where copying should begin. |
| samplesCount | int | The samples count. |
| linesCount | int | The lines count. |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | The destination format. |
| outputData | byte[] | The output data. |
| outputOffset | int | The output offset where data copying should start. |

**Returns:**
int - The converted bytes count.
