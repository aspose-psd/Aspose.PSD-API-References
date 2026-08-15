---
title: "Перечисление CompressionMethod"
type: docs
weight: 2410
url: /ru/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

Определяет метод сжатия, используемый для данных изображения.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Имя члена** | **Описание** |
| :- | :- |
| RAW | Без сжатия. Данные изображения хранятся как необработанные байты в планарном порядке RGBA.<br/>            Это означает, что сначала записываются все данные R, затем все G, затем все B и, наконец, все данные A. |
| RLE | При сжатии RLE данные изображения начинаются с подсчётов байтов для всех строк сканирования (строки * каналы), при этом каждый<br/>            подсчёт хранится как двухбайтовое значение. Затем следуют данные, сжатые RLE, при этом каждая строка сканирования сжимается отдельно.<br/>            Сжатие RLE использует тот же алгоритм, что и процедура PackBits в ROM Macintosh и стандарт TIFF. |
| ZIP_WITHOUT_PREDICTION | ZIP без предсказания. |
| ZIP_WITH_PREDICTION | ZIP с предсказанием. |
