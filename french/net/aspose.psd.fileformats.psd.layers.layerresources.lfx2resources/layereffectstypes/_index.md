---
title: Enum LayerEffectsTypes
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes énumération. Effets de fusion des calques.
type: docs
weight: 2660
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
## LayerEffectsTypes enumeration

Effets de fusion des calques.

```csharp
public enum LayerEffectsTypes
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| DropShadow | `0` | L'ombre portée. |
| OuterGlow | `1` | La lueur extérieure. |
| PatternOverlay | `2` | La superposition de motifs. |
| GradientOverlay | `3` | La superposition dégradée. |
| ColorOverlay | `4` | La superposition de couleurs. |
| Satin | `5` | Le type d'effet satiné. |
| InnerGlow | `6` | La lueur intérieure. |
| InnerShadow | `7` | L'ombre intérieure. |
| Stroke | `8` | Le trait. |
| BevelEmboss | `9` | Le biseau en relief. |

### Exemples

Le code suivant illustre la prise en charge de la propriété ILayerEffect.EffectType.

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

### Voir également

* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* Assemblée [Aspose.PSD](../../)


