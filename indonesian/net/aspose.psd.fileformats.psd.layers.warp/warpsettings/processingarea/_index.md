---
title: "WarpSettings.ProcessingArea"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti WarpSettings. Mendapatkan atau mengatur nilai ukuran area pemrosesan. Nilai default adalah 10. Rentang adalah 240."
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/processingarea/
---
{{< psd/tize >}}
## WarpSettings.ProcessingArea property

Mendapatkan atau mengatur nilai ukuran area pemrosesan. Nilai default adalah 10. Rentang adalah [2;40]

```csharp
public int ProcessingArea { get; set; }
```

## Contoh

Kode berikut menunjukkan properti WarpSettings.ProcessingArea untuk mengonfigurasi deformasi warp.

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
        // Ini mengambil WarpSettings dari Smart Layer
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // Ini mengatur ukuran area pemrosesan warp
        warpSettings.ProcessingArea = areaValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + areaValues[i] + ".png";
        outputFiles.Add(outputFile);

        // Tidak seharusnya ada kesalahan di sini
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Lihat Juga

* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


