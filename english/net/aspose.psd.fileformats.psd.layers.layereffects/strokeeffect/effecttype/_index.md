---
title: StrokeEffect.EffectType
second_title: Aspose.PSD for .NET API Reference
description: StrokeEffect property. Gets a type of effect
type: docs
weight: 20
url: /net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/effecttype/
---
{{< psd/tize >}}
## StrokeEffect.EffectType property

Gets a type of effect

```csharp
public LayerEffectsTypes EffectType { get; }
```

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

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* class [StrokeEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../strokeeffect/)
* assembly [Aspose.PSD](../../../)


