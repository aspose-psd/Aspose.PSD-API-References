---
title: Enum LayerEffectsTypes
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes opsomming. Ebenenüberblendungseffekte.
type: docs
weight: 2660
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
## LayerEffectsTypes enumeration

Ebenenüberblendungseffekte.

```csharp
public enum LayerEffectsTypes
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| DropShadow | `0` | Der Schlagschatten. |
| OuterGlow | `1` | Das äußere Leuchten. |
| PatternOverlay | `2` | Die Musterüberlagerung. |
| GradientOverlay | `3` | Die Verlaufsüberlagerung. |
| ColorOverlay | `4` | Die Farbüberlagerung. |
| Satin | `5` | Der Satin-Effekttyp. |
| InnerGlow | `6` | Das innere Leuchten. |
| InnerShadow | `7` | Der innere Schatten. |
| Stroke | `8` | Der Schlaganfall. |
| BevelEmboss | `9` | Die abgeschrägte Prägung. |

### Beispiele

Der folgende Code demonstriert die Unterstützung der ILayerEffect.EffectType-Eigenschaft.

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
            // es hat gefangen
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Siehe auch

* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* Montage [Aspose.PSD](../../)


