---
title: IGradientFillSettings.Scale
second_title: Aspose.PSD untuk Referensi .NET API
description: IGradientFillSettings Properti. Mendapat atau menyetel skala.
type: docs
weight: 100
url: /id/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

Mendapat atau menyetel skala.

```csharp
public int Scale { get; set; }
```

### Nilai properti

Skala.

### Contoh

Contoh berikut menunjukkan cara menggunakan properti Scale untuk menskalakan FillLayer dengan gradien.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // mendapatkan lapisan isian
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // perbarui nilai skala
    settings.Scale = 200;
    fillLayer.Update(); // Memperbarui data piksel

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Lihat juga

* interface [IGradientFillSettings](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* perakitan [Aspose.PSD](../../../)


