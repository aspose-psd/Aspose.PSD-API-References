---
title: ILayerEffect.EffectType
second_title: Aspose.PSD untuk Referensi .NET API
description: ILayerEffect Properti. Mendapat jenis efek
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/effecttype/
---
## ILayerEffect.EffectType property

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
* interface [ILayerEffect](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../ilayereffect/)
* perakitan [Aspose.PSD](../../../)


