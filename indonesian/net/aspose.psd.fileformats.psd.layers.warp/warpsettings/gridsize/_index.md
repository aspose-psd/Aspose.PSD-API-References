---
title: "WarpSettings.GridSize"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti WarpSettings. Mendapatkan atau mengatur ukuran kisi warp. Defaultnya adalah 1"
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

Mendapatkan atau mengatur ukuran kisi warp. Defaultnya adalah 1.

```csharp
public Size GridSize { get; set; }
```

## Contoh

Kode berikut menunjukkan dukungan properti WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Dapatkan pengaturan warp
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Atur ukuran baru
    // Untuk Photoshop nilai dapat berada di antara 1 dan 50 dan Anda tidak dapat menyimpan file PSD dengan benar.
    warpSettings.GridSize = new Size(100, 100);

    // Atur nilai yang valid
    warpSettings.GridSize = new Size(3, 3);

    // Render file contoh dengan kisi x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Lihat Juga

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


