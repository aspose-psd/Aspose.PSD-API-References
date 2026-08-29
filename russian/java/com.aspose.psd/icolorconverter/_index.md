---
title: "IColorConverter"
second_title: "Aspose.PSD for Java API Справочник"
description: "Конвертер цвета."
type: docs
weight: 116
url: /ru/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

Конвертер цвета.
## Методы

| Метод | Описание |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | Преобразует переданные данные в выходной формат. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


Преобразует переданные данные в выходной формат.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Исходный формат. |
| данные | byte[] | Исходные данные. |
| смещение | int | Смещение в байтах, с которого должно начаться копирование данных. |
| bitStart | int | Начало бита. Обратите внимание, что это значение не выровнено по байту, а представляет собой фактический бит, с которого должно начаться копирование. |
| samplesCount | int | Количество образцов. |
| linesCount | int | Количество строк. |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Формат назначения. |
| outputData | byte[] | Выходные данные. |
| outputOffset | int | Выходное смещение, с которого должно начаться копирование данных. |

**Returns:**
int — количество преобразованных байтов.
