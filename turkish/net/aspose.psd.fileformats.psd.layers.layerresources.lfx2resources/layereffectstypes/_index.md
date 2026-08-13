---
title: "Enum LayerEffectsTypes"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes enum. Katman karıştırma efektleri"
type: docs
weight: 2900
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

Katman karıştırma efektleri.

```csharp
public enum LayerEffectsTypes
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| DropShadow | `0` | Gölge. |
| OuterGlow | `1` | Dış parıltı. |
| PatternOverlay | `2` | Desen bindirme. |
| GradientOverlay | `3` | Gradyan bindirme. |
| ColorOverlay | `4` | Renk bindirme. |
| Satin | `5` | Saten Etki Türü. |
| InnerGlow | `6` | İç parıltı. |
| InnerShadow | `7` | İç gölge. |
| Stroke | `8` | Çizgi. |
| BevelEmboss | `9` | Bisel kabartma. |

## Örnekler

Aşağıdaki kod, ILayerEffect.EffectType özelliğinin desteğini gösterir.

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
            // yakalandı
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* assembly [Aspose.PSD](../../)


