---
title: "WarpSettings.ProcessingArea"
second_title: "Aspose.PSD för .NET API‑referens"
description: "WarpSettings‑egenskap. Hämtar eller anger värdet för storlek på bearbetningsområde. Standardvärdet är 10. Intervallet är 240"
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

Hämtar eller anger värdet för storlek på bearbetningsområde. Standardvärdet är 10. Intervallet är [2;40]

```csharp
public int ProcessingArea { get; set; }
```

## Exempel

Följande kod demonstrerar egenskapen WarpSettings.ProcessingArea för att konfigurera warp‑deformation.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

int[] areaValues = { 5, 10, 25, 40 };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Den hämtar WarpSettings från Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Den anger storleken på warp‑bearbetningsområdet
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // Det bör inte finnas något fel här
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Se även

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


