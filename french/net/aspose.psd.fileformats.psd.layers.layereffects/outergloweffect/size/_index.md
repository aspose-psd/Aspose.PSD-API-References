---
title: "OuterGlowEffect.Size"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété OuterGlowEffect. Obtient la valeur du flou en pixels"
type: docs
weight: 120
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/size/
---
{{< psd/tize >}}
## OuterGlowEffect.Size property

Obtient la valeur de flou en pixels.

```csharp
public int Size { get; set; }
```

### Property Value

La taille.

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


