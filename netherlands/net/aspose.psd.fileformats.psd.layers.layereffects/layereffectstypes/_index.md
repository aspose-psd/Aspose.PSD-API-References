---
title: "Enum LayerEffectsTypes"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.LayerEffectsTypes enum. Laagmengseffecten"
type: docs
weight: 2360
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

Laagmengseffecten.

```csharp
public enum LayerEffectsTypes
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| DropShadow | `0` | De slagschaduw. |
| OuterGlow | `1` | De buitenste gloed. |
| PatternOverlay | `2` | De patroonoverlay. |
| GradientOverlay | `3` | De gradientoverlay. |
| ColorOverlay | `4` | De kleurenoverlay. |
| Satin | `5` | Het satijnen Effect Type. |
| InnerGlow | `6` | De binnenste gloed. |
| InnerShadow | `7` | De binnenste schaduw. |
| Stroke | `8` | De lijn. |
| BevelEmboss | `9` | De bevel emboss. |

## Voorbeelden

De volgende code toont ondersteuning van de ILayerEffect.EffectType-eigenschap.

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
            // het werd opgevangen
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Zie ook

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


