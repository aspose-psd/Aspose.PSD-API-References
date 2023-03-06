---
title: ColorBalanceAdjustmentLayer.ShadowsMagentaGreenBalance
second_title: Aspose.PSD for .NET API Referansı
description: ColorBalanceAdjustmentLayer mülk. Gölgeler Macenta Yeşil Dengesini alır veya ayarlar.
type: docs
weight: 90
url: /tr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowsmagentagreenbalance/
---
## ColorBalanceAdjustmentLayer.ShadowsMagentaGreenBalance property

Gölgeler Macenta Yeşil Dengesini alır veya ayarlar.

```csharp
public short ShadowsMagentaGreenBalance { get; set; }
```

### Mülk değeri

Gölgeler Macenta Yeşil Dengesi.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | Gölgeler Macenta Yeşil Dengesi -100 ila +100 aralığında olmalıdır. |

### Örnekler

Aşağıdaki kod, ColorBalanceAdjustmentLayer için desteği gösterir.

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

### Ayrıca bakınız

* class [ColorBalanceAdjustmentLayer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* toplantı [Aspose.PSD](../../../)


