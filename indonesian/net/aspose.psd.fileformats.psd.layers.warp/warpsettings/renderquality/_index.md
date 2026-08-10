---
title: "WarpSettings.RenderQuality"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "WarpSettings properti. Mendapatkan atau mengatur nilai kualitas render warp antara kecepatan dan kualitas"
type: docs
weight: 50
url: /id/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

Mendapatkan atau mengatur nilai kualitas render warp - antara kecepatan dan kualitas

```csharp
public RenderQuality RenderQuality { get; set; }
```

## Contoh

Kode berikut menunjukkan properti WarpSettings.RenderQuality untuk mengonfigurasi deformasi warp.

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
        // Ini mengambil WarpSettings dari Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Ini mengatur ukuran area pemrosesan warp
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // Tidak seharusnya ada kesalahan di sini
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Lihat Juga

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


