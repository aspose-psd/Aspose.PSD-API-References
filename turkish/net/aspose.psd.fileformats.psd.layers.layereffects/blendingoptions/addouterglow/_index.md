---
title: "BlendingOptions.AddOuterGlow"
second_title: "Aspose.PSD for .NET API Referansı"
description: "BlendingOptions yöntemi. Dış parıltı efektini ekler"
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
{{< psd/tize >}}
## BlendingOptions.AddOuterGlow method

Dış parıltı efektini ekler.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Dönüş Değeri

Oluşturulan [`OuterGlowEffect`](../../outergloweffect/) nesnesi

## Örnekler

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

### Ayrıca Bakınız

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


