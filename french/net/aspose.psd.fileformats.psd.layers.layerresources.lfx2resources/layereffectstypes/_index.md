---
title: "Enum LayerEffectsTypes"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes enum. Effets de fusion de calque"
type: docs
weight: 2900
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

Effets de fusion des calques.

```csharp
public enum LayerEffectsTypes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| DropShadow | `0` | L'ombre portée. |
| OuterGlow | `1` | Lueur externe. |
| PatternOverlay | `2` | Superposition de motif. |
| GradientOverlay | `3` | Superposition de dégradé. |
| ColorOverlay | `4` | Superposition de couleur. |
| Satin | `5` | Le type d'effet satin. |
| InnerGlow | `6` | Lueur interne. |
| InnerShadow | `7` | Ombre interne. |
| Stroke | `8` | Le contour. |
| BevelEmboss | `9` | Le relief biseauté. |

## Exemples

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* assembly [Aspose.PSD](../../)


