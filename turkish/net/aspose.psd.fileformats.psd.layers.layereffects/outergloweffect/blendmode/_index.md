---
title: OuterGlowEffect.BlendMode
second_title: Aspose.PSD for .NET API Referansı
description: OuterGlowEffect mülk. Karışım modunu alır veya ayarlar.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
## OuterGlowEffect.BlendMode property

Karışım modunu alır veya ayarlar.

```csharp
public BlendMode BlendMode { get; set; }
```

### Mülk değeri

Karışım modu.

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

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [OuterGlowEffect](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* toplantı [Aspose.PSD](../../../)


