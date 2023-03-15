---
title: ColorOverlayEffect.EffectType
second_title: Aspose.PSD untuk Referensi .NET API
description: ColorOverlayEffect Properti. Mendapat jenis efek
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/effecttype/
---
## ColorOverlayEffect.EffectType property

Mendapat jenis efek

```csharp
public LayerEffectsTypes EffectType { get; }
```

### Contoh

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
            // tertangkap
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Lihat juga

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* class [ColorOverlayEffect](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../coloroverlayeffect/)
* perakitan [Aspose.PSD](../../../)


