---
title: "OuterGlowEffect.Jitter"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "OuterGlowEffect propiedad. Obtiene o establece el ruido"
type: docs
weight: 80
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/jitter/
---
{{< psd/tize >}}
## OuterGlowEffect.Jitter property

Obtiene o establece el ruido.

```csharp
public int Jitter { get; set; }
```

### Property Value

El ruido.

### Excepciones

| excepción | condición |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | El ruido debe especificarse como porcentaje en el rango de 0 a 100 |

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


