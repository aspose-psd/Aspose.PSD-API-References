---
title: Enum SampleRoundingMode
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode перечисление. Определяет способ преобразования nбитного значения в 8битное значение.
type: docs
weight: 1530
url: /ru/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

Определяет способ преобразования n-битного значения в 8-битное значение.

```csharp
public enum SampleRoundingMode
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Extrapolate | `0` | Экстраполировать 8-битное значение, чтобы уместить его в n бит, где 1 &lt; n &lt; 8. Количество всех возможных 8-битных значений равно 1 &lt;&lt; 8 = 256, от 0 до 255. Количество всех возможных n-битных значений равно 1 &lt;&lt; n, от 0 до (1 &lt;&lt; n) - 1. Наиболее разумное n-битное значение Vn, соответствующее некоторому 8-битному значению V8, равно Vn = V8 &gt;&gt; (8 - н). |
| Truncate | `1` | Усекает 8-битное значение, чтобы уместить его в n бит, где 1 &lt; n &lt; 8. Количество всех возможных n-битных значений равно 1 &lt;&lt; n, от 0 до (1 &lt;&lt; n) - 1. Наиболее разумное n-битное значение Vn, соответствующее некоторому 8-битному значению V8, равно Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* сборка [Aspose.PSD](../../)


