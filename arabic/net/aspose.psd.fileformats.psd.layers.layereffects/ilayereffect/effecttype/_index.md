---
title: "ILayerEffect.EffectType"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية ILayerEffect. يحصل على نوع التأثير"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/effecttype/
---
{{< psd/tize >}}
## ILayerEffect.EffectType property

يحصل على نوع من التأثير

```csharp
public LayerEffectsTypes EffectType { get; }
```

## أمثلة

الكود التالي يوضح دعم الخاصية ILayerEffect.EffectType.

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
            // تم التقاطه
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### انظر أيضًا

* enum [LayerEffectsTypes](../../layereffectstypes/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


