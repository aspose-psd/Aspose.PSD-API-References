---
title: "Enum LayerEffectsTypes"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Enum Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.LayerEffectsTypes. Effetti di fusione dei livelli"
type: docs
weight: 2360
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

Effetti di fusione dei livelli.

```csharp
public enum LayerEffectsTypes
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| DropShadow | `0` | L'ombra proiettata. |
| OuterGlow | `1` | Il bagliore esterno. |
| PatternOverlay | `2` | La sovrapposizione a trama. |
| GradientOverlay | `3` | La sovrapposizione a gradiente. |
| ColorOverlay | `4` | La sovrapposizione colore. |
| Satin | `5` | Il tipo di effetto satinato. |
| InnerGlow | `6` | Il bagliore interno. |
| InnerShadow | `7` | L'ombra interna. |
| Stroke | `8` | Il contorno. |
| BevelEmboss | `9` | Il rilievo a smusso. |

## Esempi

Il codice seguente dimostra il supporto della proprietà ILayerEffect.EffectType.

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
            // ha catturato
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Vedi anche

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


