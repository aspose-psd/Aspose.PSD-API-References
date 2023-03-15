---
title: ColorBalanceAdjustmentLayer.ShadowsYellowBlueBalance
second_title: Aspose.PSD untuk Referensi .NET API
description: ColorBalanceAdjustmentLayer Properti. Mendapatkan atau menyetel Shadows YellowBlue Balance.
type: docs
weight: 100
url: /id/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowsyellowbluebalance/
---
## ColorBalanceAdjustmentLayer.ShadowsYellowBlueBalance property

Mendapatkan atau menyetel Shadows YellowBlue Balance.

```csharp
public short ShadowsYellowBlueBalance { get; set; }
```

### Nilai properti

Bayangan Kuning Biru Keseimbangan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | Bayangan Kuning Biru Saldo harus berada dalam rentang dari -100 hingga +100. |

### Contoh

Kode berikut menunjukkan dukungan untuk ColorBalanceAdjustmentLayer.

```csharp
[C#]

var filePath = "ColorBalance.psd";
var outputPath = "ColorBalance_out.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    foreach (var layer in im.Layers)
    {
        var cbLayer = layer as ColorBalanceAdjustmentLayer;
        if (cbLayer != null)
        {
            cbLayer.ShadowsCyanRedBalance = 30;
            cbLayer.ShadowsMagentaGreenBalance = -15;
            cbLayer.ShadowsYellowBlueBalance = 40;
            cbLayer.MidtonesCyanRedBalance = -90;
            cbLayer.MidtonesMagentaGreenBalance = -25;
            cbLayer.MidtonesYellowBlueBalance = 20;
            cbLayer.HighlightsCyanRedBalance = -30;
            cbLayer.HighlightsMagentaGreenBalance = 67;
            cbLayer.HighlightsYellowBlueBalance = -95;
            cbLayer.PreserveLuminosity = true;
        }
    }

    im.Save(outputPath);
}
```

### Lihat juga

* class [ColorBalanceAdjustmentLayer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* perakitan [Aspose.PSD](../../../)


