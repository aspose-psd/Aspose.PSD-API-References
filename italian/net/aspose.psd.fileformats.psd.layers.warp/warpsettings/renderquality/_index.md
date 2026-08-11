---
title: "WarpSettings.RenderQuality"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà WarpSettings. Ottiene o imposta il valore della qualità di rendering della deformazione tra velocità e qualità"
type: docs
weight: 50
url: /it/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

Ottiene o imposta il valore della qualità di rendering warp - tra velocità e qualità

```csharp
public RenderQuality RenderQuality { get; set; }
```

## Esempi

Il codice seguente dimostra la proprietà WarpSettings.RenderQuality per configurare la deformazione warp.

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
        // Ottiene WarpSettings dal livello Smart
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Imposta la dimensione dell'area di elaborazione del warp
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // Non dovrebbe esserci alcun errore qui
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Vedi anche

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


