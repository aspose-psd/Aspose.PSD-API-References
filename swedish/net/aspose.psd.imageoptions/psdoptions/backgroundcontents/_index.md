---
title: "PsdOptions.BackgroundContents"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PsdOptions egenskap. Hämtar eller anger bakgrundens färg. Den kan ses under transparenta objekt"
type: docs
weight: 20
url: /sv/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

Hämtar eller anger bakgrundsfärgen. Den kan ses under transparenta objekt.

```csharp
public RawColor BackgroundContents { get; set; }
```

## Exempel

Följande kod demonstrerar stöd för BackgroundContents-egenskapen i PsdOptions.

```csharp
[C#]

// Semi-transparens behandlas fel i förhandsgranskningen av psd-filen.
// BackgroundContents tilldelas White. Transparenta områden bör ha vit färg.

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

### Se även

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


