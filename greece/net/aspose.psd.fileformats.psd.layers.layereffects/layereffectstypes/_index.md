---
title: "Enum LayerEffectsTypes"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.LayerEffectsTypes enum. Εφέ συγχώνευσης στρώματος"
type: docs
weight: 2360
url: /el/net/aspose.psd.fileformats.psd.layers.layereffects/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

Εφέ ανάμειξης στρώσεων.

```csharp
public enum LayerEffectsTypes
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| DropShadow | `0` | Η σκιά απόρριψης. |
| OuterGlow | `1` | Η εξωτερική λάμψη. |
| PatternOverlay | `2` | Η επικάλυψη μοτίβου. |
| GradientOverlay | `3` | Η επικάλυψη διαβάθμισης. |
| ColorOverlay | `4` | Η επικάλυψη χρώματος. |
| Satin | `5` | Ο τύπος εφέ σατέν. |
| InnerGlow | `6` | Η εσωτερική λάμψη. |
| InnerShadow | `7` | Η εσωτερική σκιά. |
| Stroke | `8` | Η γραμμή. |
| BevelEmboss | `9` | Η ανάγλυφη κλίση. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της ιδιότητας ILayerEffect.EffectType.

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
            // το συνέλαβε
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


