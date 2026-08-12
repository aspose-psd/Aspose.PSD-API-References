---
title: "OuterGlowEffect.BlendMode"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "OuterGlowEffect propiedad. Obtiene o establece el modo de fusión"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
{{< psd/tize >}}
## OuterGlowEffect.BlendMode property

Obtiene o establece el modo de fusión.

```csharp
public BlendMode BlendMode { get; set; }
```

### Property Value

El modo de fusión.

## Ejemplos

El siguiente código demuestra el soporte de OuterGlowEffect.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


