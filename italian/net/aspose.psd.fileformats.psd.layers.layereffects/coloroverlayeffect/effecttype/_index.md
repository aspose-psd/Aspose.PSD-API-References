---
title: ColorOverlayEffect.EffectType
second_title: Aspose.PSD per riferimento API .NET
description: ColorOverlayEffect proprietà. Ottiene un tipo di effetto
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/effecttype/
---
## ColorOverlayEffect.EffectType property

Ottiene un tipo di effetto

```csharp
public LayerEffectsTypes EffectType { get; }
```

### Esempi

Il codice seguente illustra il supporto della proprietà ILayerEffect.EffectType.

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
            // ha preso
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Guarda anche

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* class [ColorOverlayEffect](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../coloroverlayeffect/)
* assemblea [Aspose.PSD](../../../)


