---
title: Enum LayerEffectsTypes
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes Sıralama. Katman karıştırma efektleri.
type: docs
weight: 2660
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
## LayerEffectsTypes enumeration

Katman karıştırma efektleri.

```csharp
public enum LayerEffectsTypes
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| DropShadow | `0` | Alt gölge. |
| OuterGlow | `1` | Dış ışıma. |
| PatternOverlay | `2` | Desen yerleşimi. |
| GradientOverlay | `3` | Degrade yer paylaşımı. |
| ColorOverlay | `4` | Renk yerleşimi. |
| Satin | `5` | Saten Efekt Tipi. |
| InnerGlow | `6` | İç parıltı. |
| InnerShadow | `7` | İç gölge. |
| Stroke | `8` | Darbe. |
| BevelEmboss | `9` | Eğimli kabartma. |

### Örnekler

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

### Ayrıca bakınız

* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* toplantı [Aspose.PSD](../../)


