---
title: "WarpSettings.GridSize"
second_title: "Aspose.PSD för .NET API‑referens"
description: "WarpSettings-egenskap. Hämtar eller anger storleken på warp-rutnätet. Standard är 1"
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

Hämtar eller anger storleken på warp‑rutnätet. Standard är 1.

```csharp
public Size GridSize { get; set; }
```

## Exempel

Följande kod demonstrerar stöd för WarpSettings.GridSize-egenskapen.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Hämta warp‑inställningar
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Ställ in ny storlek
    // För Photoshop kan värdet vara mellan 1 och 50 och du kan inte spara PSD‑filen korrekt.
    warpSettings.GridSize = new Size(100, 100);

    // Ställ in ett giltigt värde
    warpSettings.GridSize = new Size(3, 3);

    // Rendera exempelfil med x3‑rutnät
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Se även

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


