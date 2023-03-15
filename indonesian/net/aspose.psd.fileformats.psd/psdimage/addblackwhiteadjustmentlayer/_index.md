---
title: PsdImage.AddBlackWhiteAdjustmentLayer
second_title: Aspose.PSD untuk Referensi .NET API
description: PsdImage metode. Menambahkan lapisan penyesuaian hitam putih.
type: docs
weight: 290
url: /id/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
## PsdImage.AddBlackWhiteAdjustmentLayer method

Menambahkan lapisan penyesuaian hitam putih.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### Nilai Pengembalian

Lapisan penyesuaian hitam putih yang dibuat.

### Contoh

Contoh berikut menunjukkan bagaimana Anda dapat menambahkan lapisan penyesuaian hitam putih saat runtime di Aspose.PSD

```csharp
[C#]

string sourceFileName = "Stripes.psd";
string outputFileName = "OutputStripes.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    BlackWhiteAdjustmentLayer newLayer = image.AddBlackWhiteAdjustmentLayer();
    newLayer.Name = "BlackWhiteAdjustmentLayer";
    newLayer.Reds = 22;
    newLayer.Yellows = 92;
    newLayer.Greens = 70;
    newLayer.Cyans = 79;
    newLayer.Blues = 7;
    newLayer.Magentas = 28;

    image.Save(outputFileName, new PsdOptions());
}
```

### Lihat juga

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* ruang nama [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* perakitan [Aspose.PSD](../../../)


