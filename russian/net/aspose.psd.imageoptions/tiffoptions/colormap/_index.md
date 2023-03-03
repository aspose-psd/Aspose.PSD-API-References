---
title: TiffOptions.ColorMap
second_title: Справочник по Aspose.PSD для .NET API
description: TiffOptions свойство. Получает или задает цветовую карту.
type: docs
weight: 70
url: /ru/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

Получает или задает цветовую карту.

```csharp
public ushort[] ColorMap { get; set; }
```

### Стоимость имущества

Цветовая карта.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | ценить |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | Цветовая карта может быть определена только для выборок на пиксель, равных 1. или Биты на выборку не определены. |
| ArgumentOutOfRangeException | value;Длина массива должна соответствовать следующей формуле: 3 * (2**BitsPerSample). |

### Смотрите также

* class [TiffOptions](../)
* пространство имен [Aspose.PSD.ImageOptions](../../tiffoptions/)
* сборка [Aspose.PSD](../../../)


