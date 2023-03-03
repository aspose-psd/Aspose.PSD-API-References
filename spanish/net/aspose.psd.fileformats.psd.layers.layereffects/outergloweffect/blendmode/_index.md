---
title: OuterGlowEffect.BlendMode
second_title: Referencia de API de Aspose.PSD para .NET
description: OuterGlowEffect propiedad. Obtiene o establece el modo de fusión.
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
## OuterGlowEffect.BlendMode property

Obtiene o establece el modo de fusión.

```csharp
public BlendMode BlendMode { get; set; }
```

### El valor de la propiedad

El modo de mezcla.

### Ejemplos

El siguiente código demuestra la compatibilidad con OuterGlowEffect.

```csharp
[C#]

string src = "GreenLayer.psd";
string outputPng = "output261.png";

using (var image = (PsdImage)Image.Load(src))
{
    OuterGlowEffect effect = image.Layers[1].BlendingOptions.AddOuterGlow();
    effect.Range = 10;
    effect.Spread = 10;
    ((IColorFillSettings)effect.FillColor).Color = Color.Red;
    effect.Opacity = 128;
    effect.BlendMode = BlendMode.Normal;

    image.Save(outputPng, new PngOptions());
}
```

### Ver también

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [OuterGlowEffect](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* asamblea [Aspose.PSD](../../../)


