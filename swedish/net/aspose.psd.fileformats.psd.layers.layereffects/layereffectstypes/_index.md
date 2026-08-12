---
title: "Enum LayerEffectsTypes"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.LayerEffectsTypes enum. Lagerblandningseffekter"
type: docs
weight: 2360
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

Lagerblandningseffekter.

```csharp
public enum LayerEffectsTypes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| DropShadow | `0` | Skuggfallet. |
| OuterGlow | `1` | Yttre glöd. |
| PatternOverlay | `2` | Mönsteröverlagring. |
| GradientOverlay | `3` | Gradientöverlagring. |
| ColorOverlay | `4` | Färgöverlagring. |
| Satin | `5` | Satin-effekttypen. |
| InnerGlow | `6` | Inre glöd. |
| InnerShadow | `7` | Inre skugga. |
| Stroke | `8` | Streck. |
| BevelEmboss | `9` | Kantpräglning. |

## Exempel

Följande kod visar stöd för egenskapen ILayerEffect.EffectType.

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
            // det fångades
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Se även

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


