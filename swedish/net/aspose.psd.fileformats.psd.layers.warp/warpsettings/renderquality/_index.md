---
title: "WarpSettings.RenderQuality"
second_title: "Aspose.PSD för .NET API‑referens"
description: "WarpSettings-egenskap. Hämtar eller anger värdet för warp-renderingskvalitet mellan hastighet och kvalitet"
type: docs
weight: 50
url: /sv/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

Hämtar eller anger värdet för warp‑renderingskvalitet – mellan hastighet och kvalitet

```csharp
public RenderQuality RenderQuality { get; set; }
```

## Exempel

Följande kod visar egenskapen WarpSettings.RenderQuality för att konfigurera warp‑deformation.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Den hämtar WarpSettings från Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Den anger storleken på warp‑bearbetningsområdet
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // Det bör inte finnas något fel här
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Se även

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


