---
title: Enum LayerEffectsTypes
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes enum. Efek pencampuran lapisan.
type: docs
weight: 2660
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
## LayerEffectsTypes enumeration

Efek pencampuran lapisan.

```csharp
public enum LayerEffectsTypes
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| DropShadow | `0` | Bayangan jatuh. |
| OuterGlow | `1` | Cahaya luar. |
| PatternOverlay | `2` | Hamparan pola. |
| GradientOverlay | `3` | Hamparan gradien. |
| ColorOverlay | `4` | Hamparan warna. |
| Satin | `5` | Jenis Efek Satin. |
| InnerGlow | `6` | Cahaya batin. |
| InnerShadow | `7` | Bayangan dalam. |
| Stroke | `8` | Pukulan. |
| BevelEmboss | `9` | Timbul bevel. |

### Contoh

Kode berikut menunjukkan dukungan properti ILayerEffect.EffectType.

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
            // tertangkap
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Lihat juga

* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* perakitan [Aspose.PSD](../../)


