---
title: PsdImage.AddVibranceAdjustmentLayer
second_title: Aspose.PSD untuk Referensi .NET API
description: PsdImage metode. Menambahkan lapisan penyesuaian Vibrance.
type: docs
weight: 430
url: /id/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
## PsdImage.AddVibranceAdjustmentLayer method

Menambahkan lapisan penyesuaian Vibrance.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### Nilai Pengembalian

Lapisan Vibrance yang baru dibuat.

### Contoh

Contoh kode berikut menunjukkan dukungan lapisan VibranceLayer dan kemampuan untuk mengedit penyesuaian ini.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // Membuat VibranceLayer baru
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### Lihat juga

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* ruang nama [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* perakitan [Aspose.PSD](../../../)


