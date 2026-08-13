---
title: "Enum RenderQuality"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality enum. Çarpıtmanın render kalitesini tanımlar"
type: docs
weight: 4020
url: /tr/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

Warp'ın render kalitesini açıklar.

```csharp
public enum RenderQuality
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Turbo | `4` | En hızlı seçenek, ancak kalite düşer. |
| VeryFast | `18` | Eğer hızlı bir çözüm istiyorsanız, küçük eğrilikler için uygun olabilir. |
| Fast | `35` | Kalitede küçük bir düşüşle render alımını hızlandırmanıza olanak tanır. |
| Normal | `60` | Çoğu eğrilik için önerilen değer |
| Good | `130` | Standart kaliteden daha yüksek, daha yavaş hız. Güçlü bozulmalar için önerilir. |
| Excellent | `260` | En yavaş seçenek. Güçlü bozulmalar ve yüksek çözünürlükler için önerilir. |

## Örnekler

Aşağıdaki kod, warp deformasyonunu yapılandırmak için WarpSettings.RenderQuality özelliğini gösterir.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Smart Layer'dan WarpSettings alır
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Warp işleme alanının boyutunu ayarlar
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // Burada hata olmamalı
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


