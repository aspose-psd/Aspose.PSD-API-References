---
title: "PsdOptions.BackgroundContents"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdOptions özelliği. Arka plan rengini alır veya ayarlar. Şeffaf nesnelerin altında görülebilir."
type: docs
weight: 20
url: /tr/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

Arka plan rengini alır veya ayarlar. Şeffaf nesnelerin altında görülebilir.

```csharp
public RawColor BackgroundContents { get; set; }
```

## Örnekler

Aşağıdaki kod, PsdOptions içinde BackgroundContents özelliğinin desteğini gösterir.

```csharp
[C#]

// Yarı şeffaflık, psd dosya önizlemesinde yanlış işleniyor.
// BackgroundContents beyaza atanmıştır. Şeffaf alanların beyaz renkte olması gerekir.

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

### Ayrıca Bakınız

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


