---
title: Enum LayerEffectsTypes
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes enum. Layer blending effects
type: docs
weight: 2780
url: /net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

Layer blending effects.

```csharp
public enum LayerEffectsTypes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| DropShadow | `0` | The drop shadow. |
| OuterGlow | `1` | The outer glow. |
| PatternOverlay | `2` | The pattern overlay. |
| GradientOverlay | `3` | The gradient overlay. |
| ColorOverlay | `4` | The color overlay. |
| Satin | `5` | The satin Effect Type. |
| InnerGlow | `6` | The inner glow. |
| InnerShadow | `7` | The inner shadow. |
| Stroke | `8` | The stroke. |
| BevelEmboss | `9` | The bevel emboss. |

## Examples

The following code demonstrates support of ILayerEffect.EffectType property.

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
            // it caught
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* assembly [Aspose.PSD](../../)


