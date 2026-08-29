---
title: "Перечисление CompressionMethod"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Перечисление Aspose.PSD.FileFormats.Psd.CompressionMethod. Определяет метод сжатия, используемый для данных изображения."
type: docs
weight: 1630
url: /ru/net/aspose.psd.fileformats.psd/compressionmethod/
---
{{< psd/tize >}}
## CompressionMethod enumeration

Определяет метод сжатия, используемый для данных изображения.

```csharp
public enum CompressionMethod : short
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Raw | `0` | Без сжатия. Данные изображения хранятся как необработанные байты в планарном порядке RGBA. Это означает, что сначала записываются все данные R, затем все G, затем все B и, наконец, все данные A. |
| RLE | `1` | При RLE‑сжатии данные изображения начинаются с подсчётов байтов для всех строк сканирования (строки × каналы), каждый подсчёт хранится как двухбайтовое значение. Затем следуют RLE‑сжатые данные, при этом каждая строка сжимается отдельно. RLE‑сжатие использует тот же алгоритм, что и процедура PackBits в ROM Macintosh и стандарт TIFF. |
| ZipWithoutPrediction | `2` | ZIP без предсказания. |
| ZipWithPrediction | `3` | ZIP с предсказанием. |

### См. также

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


