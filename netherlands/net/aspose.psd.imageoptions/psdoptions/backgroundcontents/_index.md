---
title: "PsdOptions.BackgroundContents"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "PsdOptions eigenschap. Haalt de kleur van de achtergrond op of stelt deze in. Deze kan worden gezien onder transparante objecten"
type: docs
weight: 20
url: /nl/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

Haalt de kleur van de achtergrond op of stelt deze in. Deze kan worden gezien onder transparante objecten.

```csharp
public RawColor BackgroundContents { get; set; }
```

## Voorbeelden

De volgende code demonstreert de ondersteuning van de BackgroundContents‑eigenschap in PsdOptions.

```csharp
[C#]

// Semi-transparantie wordt onjuist verwerkt in de preview van het psd‑bestand.
// BackgroundContents toegewezen aan Wit. Transparante gebieden moeten een witte kleur hebben.

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

### Zie ook

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


