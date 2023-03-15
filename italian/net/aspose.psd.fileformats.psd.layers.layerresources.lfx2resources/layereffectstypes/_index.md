---
title: Enum LayerEffectsTypes
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes enum. Effetti di fusione dei livelli.
type: docs
weight: 2660
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
## LayerEffectsTypes enumeration

Effetti di fusione dei livelli.

```csharp
public enum LayerEffectsTypes
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| DropShadow | `0` | L'ombra esterna. |
| OuterGlow | `1` | Il bagliore esterno. |
| PatternOverlay | `2` | La sovrapposizione del motivo. |
| GradientOverlay | `3` | La sovrapposizione sfumatura. |
| ColorOverlay | `4` | La sovrapposizione di colori. |
| Satin | `5` | Il tipo di effetto satinato. |
| InnerGlow | `6` | Il bagliore interiore. |
| InnerShadow | `7` | L'ombra interiore. |
| Stroke | `8` | Il tratto. |
| BevelEmboss | `9` | Il rilievo smussato. |

### Esempi

Il codice seguente illustra il supporto della proprietà ILayerEffect.EffectType.

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
            // ha preso
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* assemblea [Aspose.PSD](../../)


