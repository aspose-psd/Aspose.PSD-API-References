---
title: "Перечисление SampleRoundingMode"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode перечисление. Определяет способ, которым значение n‑бит преобразуется в 8‑битное значение."
type: docs
weight: 1540
url: /ru/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
{{< psd/tize >}}
## SampleRoundingMode enumeration

Определяет способ, при котором n-битное значение преобразуется в 8-битное значение.

```csharp
public enum SampleRoundingMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Extrapolate | `0` | Экстраполировать 8‑битное значение, чтобы разместить его в n битах, где 1 &lt; n &lt; 8. Количество всех возможных 8‑битных значений равно 1 &lt;&lt; 8 = 256, от 0 до 255. Количество всех возможных n‑битных значений равно 1 &lt;&lt; n, от 0 до (1 &lt;&lt; n) - 1. Наиболее разумное n‑битное значение Vn, соответствующее некоторому 8‑битному значению V8, равно Vn = V8 &gt;&gt; (8 - n). |
| Truncate | `1` | Обрезать 8‑битное значение, чтобы разместить его в n битах, где 1 &lt; n &lt; 8. Количество всех возможных n‑битных значений равно 1 &lt;&lt; n, от 0 до (1 &lt;&lt; n) - 1. Наиболее разумное n‑битное значение Vn, соответствующее некоторому 8‑битному значению V8, равно Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### См. также

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)


