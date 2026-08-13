---
title: "WarpSettings.RenderQuality"
second_title: "Aspose.PSD for .NET API Referansı"
description: "WarpSettings özelliği. Çarpıtma render kalitesi değerini alır veya ayarlar  hız ve kalite arasında"
type: docs
weight: 50
url: /tr/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

Bükülme render kalitesi değerini alır veya ayarlar - hız ve kalite arasında

```csharp
public RenderQuality RenderQuality { get; set; }
```

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

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


