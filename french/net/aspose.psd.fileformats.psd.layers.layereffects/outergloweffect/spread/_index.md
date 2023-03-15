---
title: OuterGlowEffect.Spread
second_title: Référence de l'API Aspose.PSD pour .NET
description: OuterGlowEffect propriété. Obtient ou définit lintensité sous forme de pourcentage.
type: docs
weight: 130
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/spread/
---
## OuterGlowEffect.Spread property

Obtient ou définit l'intensité sous forme de pourcentage.

```csharp
public int Spread { get; set; }
```

### Valeur de la propriété

La propagation.

### Exemples

Le code suivant illustre la prise en charge d'OuterGlowEffect.

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

### Voir également

* class [OuterGlowEffect](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../outergloweffect/)
* Assemblée [Aspose.PSD](../../../)


