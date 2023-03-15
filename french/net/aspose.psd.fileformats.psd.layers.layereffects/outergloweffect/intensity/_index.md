---
title: OuterGlowEffect.Intensity
second_title: Référence de l'API Aspose.PSD pour .NET
description: OuterGlowEffect propriété. Obtient ou définit langle en degrés.
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/intensity/
---
## OuterGlowEffect.Intensity property

Obtient ou définit l'angle en degrés.

```csharp
public int Intensity { get; set; }
```

### Valeur de la propriété

L'angle.

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


