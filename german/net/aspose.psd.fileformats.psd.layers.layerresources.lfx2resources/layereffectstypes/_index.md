---
title: "Enum LayerEffectsTypes"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes Enum. Ebenenüberblendungseffekte"
type: docs
weight: 2900
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

Layer‑Blending‑Effekte.

```csharp
public enum LayerEffectsTypes
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| DropShadow | `0` | Der Schlagschatten. |
| OuterGlow | `1` | Das äußere Leuchten. |
| PatternOverlay | `2` | Die Musterüberlagerung. |
| GradientOverlay | `3` | Die Farbverlauf-Überlagerung. |
| ColorOverlay | `4` | Die Farbüberlagerung. |
| Satin | `5` | Der Satin-Effekttyp. |
| InnerGlow | `6` | Das innere Leuchten. |
| InnerShadow | `7` | Der innere Schatten. |
| Stroke | `8` | Der Strich. |
| BevelEmboss | `9` | Die Schrägkantprägung. |

## Beispiele

Der folgende Code demonstriert die Unterstützung der ILayerEffect.EffectType‑Eigenschaft.

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
            // es wurde abgefangen
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* assembly [Aspose.PSD](../../)


