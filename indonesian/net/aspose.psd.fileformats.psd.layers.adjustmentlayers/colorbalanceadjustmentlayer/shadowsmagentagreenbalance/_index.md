---
title: "ColorBalanceAdjustmentLayer.ShadowsMagentaGreenBalance"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti ColorBalanceAdjustmentLayer. Mendapatkan atau mengatur Keseimbangan Magenta Hijau Bayangan."
type: docs
weight: 90
url: /id/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowsmagentagreenbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.ShadowsMagentaGreenBalance property

Mendapatkan atau mengatur Shadows Magenta Green Balance.

```csharp
public short ShadowsMagentaGreenBalance { get; set; }
```

### Property Value

Keseimbangan Magenta Hijau Bayangan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | Keseimbangan Magenta Hijau Bayangan harus berada dalam rentang -100 hingga +100. |

## Contoh

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

### Lihat Juga

* class [ColorBalanceAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


