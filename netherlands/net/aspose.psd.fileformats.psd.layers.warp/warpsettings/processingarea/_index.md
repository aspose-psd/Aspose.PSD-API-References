---
title: "WarpSettings.ProcessingArea"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "WarpSettings property. Haalt of stelt de waarde van de grootte van het verwerkingsgebied in. Standaardwaarde is 10. Bereik is 240"
type: docs
weight: 40
url: /nl/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

Haalt of stelt de waarde van de grootte van het verwerkingsgebied in. Standaardwaarde is 10. Bereik is [2;40]

```csharp
public int ProcessingArea { get; set; }
```

## Voorbeelden

De volgende code toont WarpSettings.ProcessingArea property om warp-deformatie te configureren.

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
        // Het haalt WarpSettings op van de Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Het stelt de grootte van het warp-verwerkingsgebied in
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // Er zou hier geen fout moeten zijn
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Zie ook

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


