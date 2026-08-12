---
title: "Enum RenderQuality"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality enum. Den beskriver renderingskvaliteten för Warp"
type: docs
weight: 3990
url: /sv/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

Den beskriver renderingskvaliteten för Warp.

```csharp
public enum RenderQuality
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Turbo | `4` | Det snabbaste alternativet, men kvaliteten försämras. |
| VeryFast | `18` | Om du behöver det snabbt kan det vara lämpligt för små krökningar. |
| Fast | `35` | Gör det möjligt att snabba upp rendering med en liten kvalitetsförlust. |
| Normal | `60` | Rekommenderat värde för de flesta krökningar |
| Good | `130` | Högre än standardkvalitet, långsammare hastighet. Rekommenderas för starka förvrängningar. |
| Excellent | `260` | Det långsammaste alternativet. Rekommenderas för starka förvrängningar och hög upplösning. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


