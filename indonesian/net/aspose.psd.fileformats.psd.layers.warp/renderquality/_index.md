---
title: "Enum RenderQuality"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality enum. Menjelaskan kualitas rendering Warp"
type: docs
weight: 3990
url: /id/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

Ini menjelaskan kualitas rendering Warp.

```csharp
public enum RenderQuality
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Turbo | `4` | Opsi tercepat, tetapi kualitasnya menurun. |
| VeryFast | `18` | Jika Anda membutuhkannya cepat, ini mungkin cocok untuk kelengkungan kecil. |
| Fast | `35` | Memungkinkan Anda mempercepat rendering dengan sedikit penurunan kualitas. |
| Normal | `60` | Nilai yang direkomendasikan untuk kebanyakan kelengkungan |
| Good | `130` | Kualitas lebih tinggi daripada standar, kecepatan lebih lambat. Direkomendasikan untuk distorsi kuat. |
| Excellent | `260` | Opsi paling lambat. Direkomendasikan untuk distorsi kuat dan resolusi tinggi. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


