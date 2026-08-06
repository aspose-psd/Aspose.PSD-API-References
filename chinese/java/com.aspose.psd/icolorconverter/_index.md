---
title: "IColorConverter"
second_title: "Aspose.PSD 的 Java API 参考"
description: "颜色转换器。"
type: docs
weight: 116
url: /zh/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

颜色转换器。
## Methods

| Method | 描述 |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | 将传入的数据转换为输出格式。 |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


将传入的数据转换为输出格式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 源格式。 |
| data | byte[] | 源数据。 |
| offset | int | 数据复制应开始的字节偏移量。 |
| bitStart | int | 位起始。注意，此值不是字节对齐的，而是实际的位，复制应从该位开始。 |
| samplesCount | int | 样本计数。 |
| linesCount | int | 行计数。 |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 目标格式。 |
| outputData | byte[] | 输出数据。 |
| outputOffset | int | 数据复制应开始的输出偏移。 |

**Returns:**
int - 转换的字节计数。
