---
title: OuterGlowEffect.Range
second_title: Référence de l'API Aspose.PSD pour .NET
description: OuterGlowEffect propriété. Obtient ou définit le bruit.
type: docs
weight: 110
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/range/
---
## OuterGlowEffect.Range property

Obtient ou définit le bruit.

```csharp
public int Range { get; set; }
```

### Valeur de la propriété

Le bruit.

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Le bruit doit être spécifié en pourcentage dans la plage de 0 à 100 |

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


