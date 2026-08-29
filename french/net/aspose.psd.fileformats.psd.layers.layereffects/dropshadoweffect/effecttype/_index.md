---
title: "DropShadowEffect.EffectType"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété DropShadowEffect. Obtient un type d'effet"
type: docs
weight: 50
url: /fr/net/aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/effecttype/
---
{{< psd/tize >}}
## DropShadowEffect.EffectType property

Obtient un type d'effet

```csharp
public LayerEffectsTypes EffectType { get; }
```

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

Le code suivant montre la prise en charge de la propriété ILayerEffect.EffectType.

```csharp
[C#]

string inputFile = "input.psd";
string outputWithout = "outputWithout.png";
string outputWith = "outputWith.png";

using (PsdImage psdImage = (PsdImage)Image.Load(inputFile, new LoadOptions()))
{
    psdImage.Save(outputWithout, new PngOptions());

    Layer workLayer = psdImage.Layers[1];

    DropShadowEffect dropShadowEffect = workLayer.BlendingOptions.AddDropShadow();
    dropShadowEffect.Distance = 0;
    dropShadowEffect.Size = 8;
    dropShadowEffect.Opacity = 20;

    foreach (ILayerEffect iEffect in workLayer.BlendingOptions.Effects)
    {
        if (iEffect.EffectType == LayerEffectsTypes.DropShadow)
        {
            // il a attrapé
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Voir aussi

* enum [LayerEffectsTypes](../../layereffectstypes/)
* class [DropShadowEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


