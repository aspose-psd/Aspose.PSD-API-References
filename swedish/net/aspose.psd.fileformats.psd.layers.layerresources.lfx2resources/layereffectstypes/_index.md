---
title: Enum LayerEffectsTypes
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes uppräkning. Lagerblandningseffekter.
type: docs
weight: 2660
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
## LayerEffectsTypes enumeration

Lagerblandningseffekter.

```csharp
public enum LayerEffectsTypes
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| DropShadow | `0` | Skuggan. |
| OuterGlow | `1` | Den yttre glöden. |
| PatternOverlay | `2` | Mönsteröverlagringen. |
| GradientOverlay | `3` | Gradientöverlagringen. |
| ColorOverlay | `4` | Färgöverlägget. |
| Satin | `5` | The satin Effect Type. |
| InnerGlow | `6` | Den inre glöden. |
| InnerShadow | `7` | Den inre skuggan. |
| Stroke | `8` | Slaget. |
| BevelEmboss | `9` | Fasad relief. |

### Exempel

Följande kod visar stöd för ILayerEffect.EffectType-egenskapen.

```csharp
[C#]

string inputFile = "input.psd";
string outputWithout = "outputWithout.png";
string outputWith = "outputWith.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    psdImage.Save(outputWithout, new PngOptions());

    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;
    dropShadowEffect.Opacity = 20;

    foreach (ILayerEffect iEffect in workLayer.BlendingOptions.Effects)
    {
        if (iEffect.EffectType == LayerEffectsTypes.DropShadow)
        {
            // det fångade
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Se även

* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* hopsättning [Aspose.PSD](../../)


