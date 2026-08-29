---
title: "BlendingOptions.AddOuterGlow"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode BlendingOptions. Ajoute l'effet de lueur externe"
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/addouterglow/
---
{{< psd/tize >}}
## BlendingOptions.AddOuterGlow method

Ajoute l'effet de lueur externe.

```csharp
public OuterGlowEffect AddOuterGlow()
```

### Valeur de retour

Créé l'objet [`OuterGlowEffect`](../../outergloweffect/)

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

* class [OuterGlowEffect](../../outergloweffect/)
* class [BlendingOptions](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


