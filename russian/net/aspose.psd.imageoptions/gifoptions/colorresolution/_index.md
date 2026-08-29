---
title: "GifOptions.ColorResolution"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство GifOptions. Получает или задает цветовое разрешение GIF"
type: docs
weight: 30
url: /ru/net/aspose.psd.imageoptions/gifoptions/colorresolution/
---
{{< psd/tize >}}
## GifOptions.ColorResolution property

Получает или задает разрешение цвета GIF.

```csharp
public byte ColorResolution { get; set; }
```

### Property Value

Цветовое разрешение.

## Примечания

Color Resolution — количество бит на основной цвет, доступных в исходном изображении, минус 1. Это значение представляет размер всей палитры, из которой были выбраны цвета графики, а не количество фактически использованных цветов в графике. Например, если значение в этом поле равно 3, то палитра исходного изображения имела 4 бита на основной цвет, доступные для создания изображения. Это значение следует задавать, чтобы указать насыщенность оригинальной палитры, даже если не каждый цвет из полной палитры доступен на исходном устройстве.

### См. также

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


