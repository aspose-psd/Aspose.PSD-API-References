---
title: PatternOverlayEffect.EffectType
second_title: Referencia de API de Aspose.PSD para .NET
description: PatternOverlayEffect propiedad. Obtiene un tipo de efecto type
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/effecttype/
---
## PatternOverlayEffect.EffectType property

Obtiene un tipo de efecto type

```csharp
public LayerEffectsTypes EffectType { get; }
```

### Ejemplos

El siguiente código demuestra la compatibilidad con la propiedad ILayerEffect.EffectType.

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
            // atrapó
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Ver también

* enum [LayerEffectsTypes](../../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/)
* class [PatternOverlayEffect](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../patternoverlayeffect/)
* asamblea [Aspose.PSD](../../../)


