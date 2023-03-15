---
title: OuterGlowEffect.Range
second_title: Referencia de API de Aspose.PSD para .NET
description: OuterGlowEffect propiedad. Obtiene o establece el ruido.
type: docs
weight: 110
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/
---
## OuterGlowEffect.Range property

Obtiene o establece el ruido.

```csharp
public int Range { get; set; }
```

### El valor de la propiedad

El ruido.

### Excepciones

| excepción | condición |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | El ruido debe especificarse como porcentaje en un rango de 0 a 100 |

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

* class [OuterGlowEffect](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* asamblea [Aspose.PSD](../../../)


