---
title: "DropShadowEffect.IsVisible"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété DropShadowEffect. Obtient ou définit une valeur indiquant si cette instance est visible"
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/isvisible/
---
{{< psd/tize >}}
## DropShadowEffect.IsVisible property

Obtient ou définit une valeur indiquant si cette instance est visible.

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` si cette instance est visible ; sinon, `false`.

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

* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


