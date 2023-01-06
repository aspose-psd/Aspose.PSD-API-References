---
title: ReadULongArray
second_title: Справочник по Aspose.PSD для .NET API
description: Считывает из потока массив целочисленных значений без знака.
type: docs
weight: 200
url: /ru/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readulongarray/
---
## TiffStreamReader.ReadULongArray method

Считывает из потока массив целочисленных значений без знака.

```csharp
public uint[] ReadULongArray(long position, long count)
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
| ArgumentOutOfRangeException | count;Общее количество байтов отрицательное. + count + x4= + totalBytes |

### Смотрите также

* class [TiffStreamReader](../../tiffstreamreader)
* пространство имен [Aspose.PSD.FileFormats.Tiff.FileManagement](../../tiffstreamreader)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->