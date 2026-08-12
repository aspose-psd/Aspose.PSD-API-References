---
title: "PsdOptions.BackgroundContents"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство PsdOptions. Получает или задает цвет фона. Он виден под прозрачными объектами"
type: docs
weight: 20
url: /ru/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

Получает или задает цвет фона. Он виден под прозрачными объектами.

```csharp
public RawColor BackgroundContents { get; set; }
```

## Примеры

Следующий код демонстрирует поддержку свойства BackgroundContents в PsdOptions.

```csharp
[C#]

// Полупрозрачность обрабатывается неправильно в предварительном просмотре файла psd.
// BackgroundContents назначен в White. Прозрачные области должны иметь белый цвет.

string sourceFile = "frog_nosymb.psd";
string outputFile = "frog_nosymb_backgroundcontents_output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    RawColor backgroundColor = new RawColor(PixelDataFormat.Rgb32Bpp);
    int argbValue = 255 << 24 | 255 << 16 | 255 << 8 | 255;
    backgroundColor.SetAsInt(argbValue); // White

    PsdOptions psdOptions = new PsdOptions(psdImage)
    {
        ColorMode = ColorModes.Rgb,
        CompressionMethod = CompressionMethod.RLE,
        ChannelsCount = 4,
        BackgroundContents = backgroundColor,
    };

    psdImage.Save(outputFile, psdOptions);
}
```

### См. также

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


