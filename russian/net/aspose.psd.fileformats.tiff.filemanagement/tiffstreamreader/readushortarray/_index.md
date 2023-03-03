---
title: TiffStreamReader.ReadUShortArray
second_title: Справочник по Aspose.PSD для .NET API
description: TiffStreamReader метод. Считывает из потока массив целочисленных значений без знака.
type: docs
weight: 220
url: /ru/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readushortarray/
---
## TiffStreamReader.ReadUShortArray method

Считывает из потока массив целочисленных значений без знака.

```csharp
public ushort[] ReadUShortArray(long position, long count)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| position | Int64 | Позиция для чтения. |
| count | Int64 | Элементы считаются. |

### Возвращаемое значение

Массив целочисленных значений без знака.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | count;Общее количество байтов отрицательное. + count + x2= + totalBytes |

### Смотрите также

* class [TiffStreamReader](../)
* пространство имен [Aspose.PSD.FileFormats.Tiff.FileManagement](../../tiffstreamreader/)
* сборка [Aspose.PSD](../../../)


