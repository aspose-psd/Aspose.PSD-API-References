---
title: "IGradientFillSettings.Scale"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "IGradientFillSettings properti. Mendapatkan atau mengatur skala gradien ternormalkan dalam persen"
type: docs
weight: 90
url: /id/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
{{< psd/tize >}}
## IGradientFillSettings.Scale property

Mendapatkan atau mengatur skala gradien **normalized** (dalam persen).

```csharp
public int Scale { get; set; }
```

### Property Value

Skala.

## Contoh

Contoh berikut menunjukkan cara menggunakan properti Scale untuk memperbesar FillLayer dengan gradien.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // mengambil lapisan isi
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

    // memperbarui nilai skala
    settings.Scale = 200;
    fillLayer.Update(); // Updates pixels data

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Lihat Juga

* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


