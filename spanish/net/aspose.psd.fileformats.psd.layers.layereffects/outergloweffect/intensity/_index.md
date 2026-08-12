---
title: "OuterGlowEffect.Intensity"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "OuterGlowEffect propiedad. Obtiene o establece el ángulo en grados"
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
{{< psd/tize >}}
## OuterGlowEffect.Intensity property

Obtiene o establece el ángulo en grados.

```csharp
public int Intensity { get; set; }
```

### Property Value

El ángulo.

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

* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


