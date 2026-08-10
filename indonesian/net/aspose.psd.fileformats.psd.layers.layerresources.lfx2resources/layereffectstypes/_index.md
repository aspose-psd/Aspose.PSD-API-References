---
title: "Enum LayerEffectsTypes"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources.LayerEffectsTypes enum. Efek pencampuran lapisan"
type: docs
weight: 2900
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/layereffectstypes/
---
{{< psd/tize >}}
## LayerEffectsTypes enumeration

Efek pencampuran lapisan.

```csharp
public enum LayerEffectsTypes
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| DropShadow | `0` | Bayangan jatuh. |
| OuterGlow | `1` | Cahaya luar. |
| PatternOverlay | `2` | Lapisan pola. |
| GradientOverlay | `3` | Lapisan gradasi. |
| ColorOverlay | `4` | Lapisan warna. |
| Satin | `5` | Tipe Efek satin. |
| InnerGlow | `6` | Cahaya dalam. |
| InnerShadow | `7` | Bayangan dalam. |
| Stroke | `8` | Garis tepi. |
| BevelEmboss | `9` | Ukiran bevel. |

## Contoh

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
            // itu tertangkap
            psdImage.Save(outputWith, new PngOptions());
        }
    }
}
```

### Lihat Juga

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lfx2Resources](../../aspose.psd.fileformats.psd.layers.layerresources.lfx2resources/)
* assembly [Aspose.PSD](../../)


