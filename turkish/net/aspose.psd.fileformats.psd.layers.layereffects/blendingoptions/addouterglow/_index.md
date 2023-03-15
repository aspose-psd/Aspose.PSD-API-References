---
title: BlendingOptions.AddOuterGlow
second_title: Aspose.PSD for .NET API Referansı
description: BlendingOptions yöntem. Dış ışıma efektini ekler.
type: docs
weight: 60
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
## BlendingOptions.AddOuterGlow method

Dış ışıma efektini ekler.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Geri dönüş değeri

Oluşturuldu[`OuterGlowEffect`](../../outergloweffect/) nesne

### Örnekler

Aşağıdaki kod, OuterGlowEffect desteğini gösterir.

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

### Ayrıca bakınız

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../blendingoptions/)
* toplantı [Aspose.PSD](../../../)


