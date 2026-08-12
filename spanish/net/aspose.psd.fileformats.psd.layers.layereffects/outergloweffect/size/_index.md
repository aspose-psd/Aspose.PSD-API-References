---
title: "OuterGlowEffect.Size"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "OuterGlowEffect propiedad. Obtiene el valor de desenfoque en píxeles"
type: docs
weight: 120
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/
---
{{< psd/tize >}}
## OuterGlowEffect.Size property

Obtiene el valor de desenfoque en píxeles.

```csharp
public int Size { get; set; }
```

### Property Value

El tamaño.

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


