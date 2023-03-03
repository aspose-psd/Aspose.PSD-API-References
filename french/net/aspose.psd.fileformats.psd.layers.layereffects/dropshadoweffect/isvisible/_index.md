---
title: DropShadowEffect.IsVisible
second_title: Référence de l'API Aspose.PSD pour .NET
description: DropShadowEffect propriété. Obtient ou définit une valeur indiquant si cette instance est visible.
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
## DropShadowEffect.IsVisible property

Obtient ou définit une valeur indiquant si cette instance est visible.

```csharp
public bool IsVisible { get; set; }
```

### Valeur de la propriété

`vrai` si cette instance est visible ; sinon,`FAUX` .

### Exemples

Le code suivant illustre l'utilisation de la propriété Opacity de DropShadowEffect.

```csharp
[C#]

string inputFile = "input.psd";
string outputImage20 = "outputImage20.png";
string outputImage200 = "outputImage200.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;

    // Exemple avec Opacité = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Exemple avec Opacité = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Voir également

* class [DropShadowEffect](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../dropshadoweffect/)
* Assemblée [Aspose.PSD](../../../)


