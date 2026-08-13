---
title: "WarpSettings.ProcessingArea"
second_title: "Aspose.PSD for .NET API Referansı"
description: "WarpSettings özelliği. İşleme alanı boyutunun değerini alır veya ayarlar. Varsayılan değer 10'dur. Aralık 240'tır"
type: docs
weight: 40
url: /tr/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

İşleme alanı boyutunun değerini alır veya ayarlar. Varsayılan değer 10'dur. Aralık [2;40]'dır

```csharp
public int ProcessingArea { get; set; }
```

## Örnekler

Aşağıdaki kod, çarpıtma deformasyonunu yapılandırmak için WarpSettings.ProcessingArea özelliğini gösterir.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

int[] areaValues = { 5, 10, 25, 40 };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Smart Layer'dan WarpSettings alır
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Warp işleme alanının boyutunu ayarlar
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // Burada hata olmamalı
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Ayrıca Bakınız

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


