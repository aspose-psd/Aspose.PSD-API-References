---
title: "GradientOverlayEffect.EffectType"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "GradientOverlayEffect properti. Mendapatkan tipe efek"
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/effecttype/
---
{{< psd/tize >}}
## GradientOverlayEffect.EffectType property

Mendapatkan tipe efek

```csharp
public LayerEffectsTypes EffectType { get; }
```

## Contoh

Kode berikut menunjukkan dukungan properti ILayerEffect.EffectType.

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
            // itu tertangkap
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Lihat Juga

* enum [LayerEffectsTypes](../../layereffectstypes/)
* class [GradientOverlayEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


