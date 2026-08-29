---
title: "PsdOptions.BackgroundContents"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdOptions-Eigenschaft. Gibt die Hintergrundfarbe zurück oder legt sie fest. Sie ist unter transparenten Objekten sichtbar."
type: docs
weight: 20
url: /de/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

Liest oder setzt die Hintergrundfarbe. Sie kann bei transparenten Objekten gesehen werden.

```csharp
public RawColor BackgroundContents { get; set; }
```

## Beispiele

Der folgende Code demonstriert die Unterstützung der BackgroundContents-Eigenschaft in PsdOptions.

```csharp
[C#]

// Halbtransparenz wird in der PSD-Dateivorschau falsch verarbeitet.
// BackgroundContents ist auf Weiß gesetzt. Transparente Bereiche sollten die weiße Farbe haben.

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

### Siehe auch

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


