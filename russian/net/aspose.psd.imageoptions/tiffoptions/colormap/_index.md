---
title: "TiffOptions.ColorMap"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство TiffOptions. Получает или задает карту цветов"
type: docs
weight: 70
url: /ru/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
{{< psd/tize >}}
## TiffOptions.ColorMap property

Получает или задает карту цветов.

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

Карта цветов.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | значение |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | Карта цветов может быть определена только для samples per pixel, равного 1. или биты на образец не определены. |
| ArgumentOutOfRangeException | value;Длина массива должна соответствовать следующей формуле: 3 * (2**BitsPerSample). |

### См. также

* class [TiffOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


