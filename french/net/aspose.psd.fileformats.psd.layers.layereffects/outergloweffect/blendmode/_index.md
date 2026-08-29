---
title: "OuterGlowEffect.BlendMode"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété OuterGlowEffect. Obtient ou définit le mode de fusion"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/blendmode/
---
{{< psd/tize >}}
## OuterGlowEffect.BlendMode property

Obtient ou définit le mode de fusion.

```csharp
public BlendMode BlendMode { get; set; }
```

### Property Value

Le mode de fusion.

## Exemples

Le code suivant montre la prise en charge de OuterGlowEffect.

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

### Voir aussi

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


