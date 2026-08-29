---
title: "GradientOverlayEffect.EffectType"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad GradientOverlayEffect. Obtiene un tipo de efecto"
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/effecttype/
---
{{< psd/tize >}}
## GradientOverlayEffect.EffectType property

Obtiene un tipo de efecto

```csharp
public LayerEffectsTypes EffectType { get; }
```

## Ejemplos

El siguiente código demuestra el soporte de la propiedad ILayerEffect.EffectType.

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
            // lo atrapó
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Ver también

* enum [LayerEffectsTypes](../../layereffectstypes/)
* class [GradientOverlayEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


