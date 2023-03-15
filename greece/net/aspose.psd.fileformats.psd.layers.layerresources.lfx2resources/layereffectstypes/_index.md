---
title: Enum LayerEffectsTypes
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes αρίθμηση. Εφέ ανάμειξης επιπέδων.
type: docs
weight: 2660
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
## LayerEffectsTypes enumeration

Εφέ ανάμειξης επιπέδων.

```csharp
public enum LayerEffectsTypes
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| DropShadow | `0` | Η σκιά. |
| OuterGlow | `1` | Η εξωτερική λάμψη. |
| PatternOverlay | `2` | Η επικάλυψη μοτίβου. |
| GradientOverlay | `3` | Η επικάλυψη ντεγκραντέ. |
| ColorOverlay | `4` | Η επικάλυψη χρώματος. |
| Satin | `5` | Ο τύπος εφέ σατέν. |
| InnerGlow | `6` | Η εσωτερική λάμψη. |
| InnerShadow | `7` | Η εσωτερική σκιά. |
| Stroke | `8` | Το εγκεφαλικό. |
| BevelEmboss | `9` | Το λοξότμητο ανάγλυφο. |

### Παραδείγματα

Ο ακόλουθος κώδικας δείχνει την υποστήριξη της ιδιότητας ILayerEffect.EffectType.

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
            // έπιασε
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* συνέλευση [Aspose.PSD](../../)


