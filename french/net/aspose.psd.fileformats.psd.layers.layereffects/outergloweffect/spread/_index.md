---
title: "OuterGlowEffect.Spread"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété OuterGlowEffect. Obtient ou définit l'intensité en pourcentage"
type: docs
weight: 130
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/
---
{{< psd/tize >}}
## OuterGlowEffect.Spread property

Obtient ou définit l'intensité en pourcentage.

```csharp
public int Spread { get; set; }
```

### Property Value

L'étalement.

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

* class [OuterGlowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


