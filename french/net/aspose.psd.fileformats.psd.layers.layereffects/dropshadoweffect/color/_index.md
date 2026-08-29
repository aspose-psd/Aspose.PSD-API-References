---
title: "DropShadowEffect.Color"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété DropShadowEffect. Obtient ou définit la couleur"
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/color/
---
{{< psd/tize >}}
## DropShadowEffect.Color property

Obtient ou définit la couleur.

```csharp
public Color Color { get; set; }
```

### Property Value

La couleur.

## Exemples

Le code suivant montre l'utilisation de la propriété Opacity de DropShadowEffect.

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

    // Exemple avec Opacity = 20
    dropShadowEffect.Opacity = 20;
    psdImage.Save(outputImage20, new PngOptions());

    // Exemple avec Opacity = 200
    dropShadowEffect.Opacity = 200;
    psdImage.Save(outputImage200, new PngOptions());
}
```

### Voir aussi

* struct [Color](../../../aspose.psd/color/)
* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


