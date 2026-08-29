---
title: "TiffStreamReader.ReadUShortArray"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод TiffStreamReader. Считывает массив беззнаковых целочисленных значений из потока"
type: docs
weight: 220
url: /ru/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readushortarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadUShortArray method

Считывает массив беззнаковых целочисленных значений из потока.

```csharp
public ushort[] ReadUShortArray(long position, long count)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | Int64 | Позиция, из которой читать. |
| count | Int64 | Количество элементов. |

### Возвращаемое значение

Массив беззнаковых целочисленных значений.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | count;Общее количество байтов отрицательно. + count + x2= + totalBytes |

### См. также

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


