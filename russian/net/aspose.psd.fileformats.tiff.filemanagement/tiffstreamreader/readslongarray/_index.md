---
title: "TiffStreamReader.ReadSLongArray"
second_title: "Справочник API Aspose.PSD для .NET"
description: "TiffStreamReader method. Считывает массив знаковых целочисленных значений из потока"
type: docs
weight: 140
url: /ru/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadSLongArray method

Считывает массив знаковых целочисленных значений из потока.

```csharp
public int[] ReadSLongArray(long position, long count)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | Int64 | Позиция, из которой читать. |
| count | Int64 | Количество элементов. |

### Возвращаемое значение

Массив знаковых целочисленных значений.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | count;Общее количество байтов отрицательно. + count + x4= + totalBytes |

### См. также

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


