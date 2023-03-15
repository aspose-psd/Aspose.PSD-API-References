---
title: Enum CompressionMethod
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.CompressionMethod перечисление. Определяет метод сжатия используемый для данных изображения.
type: docs
weight: 1620
url: /ru/net/aspose.psd.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

Определяет метод сжатия, используемый для данных изображения.

```csharp
public enum CompressionMethod : short
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Raw | `0` | Без сжатия. Данные изображения хранятся в виде необработанных байтов в планерном порядке RGBA. Это означает, что сначала записываются все данные R, затем записываются все данные G, затем записываются все данные B и, наконец, записываются все данные A. |
| RLE | `1` | RLE-сжатие данных изображения начинается с подсчета байтов для всех строк сканирования (строки * каналы), при этом каждый счетчик хранится в виде двухбайтового значения. Далее следуют сжатые данные RLE, причем каждая строка сканирования сжимается отдельно. Сжатие RLE — это тот же алгоритм сжатия, который используется подпрограммой Macintosh ROM PackBits и стандартом TIFF. |
| ZipWithoutPrediction | `2` | ZIP без предсказания. |
| ZipWithPrediction | `3` | ZIP с предсказанием. |

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* сборка [Aspose.PSD](../../)


