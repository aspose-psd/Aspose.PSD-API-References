---
title: ColorBalanceAdjustmentLayer.HighlightsMagentaGreenBalance
second_title: Aspose.PSD untuk Referensi .NET API
description: ColorBalanceAdjustmentLayer Properti. Mendapatkan atau menyetel Sorotan Magenta Green Balance.
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/highlightsmagentagreenbalance/
---
## ColorBalanceAdjustmentLayer.HighlightsMagentaGreenBalance property

Mendapatkan atau menyetel Sorotan Magenta Green Balance.

```csharp
public short HighlightsMagentaGreenBalance { get; set; }
```

### Nilai properti

Sorotan Magenta Green Balance.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | Sorotan Magenta Green Balance harus berkisar dari -100 hingga +100. |

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


