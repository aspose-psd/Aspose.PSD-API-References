---
title: "IColorConverter.Convert"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод IColorConverter. Преобразует переданные данные в выходной формат"
type: docs
weight: 10
url: /ru/net/aspose.psd/icolorconverter/convert/
---
{{< psd/tize >}}
## IColorConverter.Convert method

Преобразует переданные данные в выходной формат.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | Исходный формат. |
| данные | Byte[] | Исходные данные. |
| offset | Int32 | Смещение в байтах, с которого должно начаться копирование данных. |
| bitStart | Int32 | Начало бита. Обратите внимание, что это значение не выровнено по байту, а представляет собой фактический бит, с которого должно начаться копирование. |
| samplesCount | Int32 | Количество образцов. |
| linesCount | Int32 | Количество строк. |
| destFormat | PixelDataFormat | Формат назначения. |
| outputData | Byte[] | Выходные данные. |
| outputOffset | Int32 | Выходное смещение, с которого должно начаться копирование данных. |

### Возвращаемое значение

Количество преобразованных байтов.

### См. также

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


