---
title: BlendingOptions.AddOuterGlow
second_title: Referencia de API de Aspose.PSD para .NET
description: BlendingOptions método. Agrega el efecto de brillo exterior.
type: docs
weight: 60
url: /es/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

Agrega el efecto de brillo exterior.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Valor_devuelto

Creado[`OuterGlowEffect`](../../outergloweffect/) objeto

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

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions/)
* asamblea [Aspose.PSD](../../../)


