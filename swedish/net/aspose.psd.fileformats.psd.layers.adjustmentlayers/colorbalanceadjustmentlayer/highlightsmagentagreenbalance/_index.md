---
title: ColorBalanceAdjustmentLayer.HighlightsMagentaGreenBalance
second_title: Aspose.PSD för .NET API-referens
description: ColorBalanceAdjustmentLayer fast egendom. Får eller ställer in Highlights Magenta Green Balance.
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/highlightsmagentagreenbalance/
---
## ColorBalanceAdjustmentLayer.HighlightsMagentaGreenBalance property

Får eller ställer in Highlights Magenta Green Balance.

```csharp
public short HighlightsMagentaGreenBalance { get; set; }
```

### Fastighetsvärde

The Highlights Magenta Green Balance.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | Höjdpunkter Magenta grönbalans måste ligga inom området -100 till +100. |

### Exempel

Följande kod visar stöd för ColorBalanceAdjustmentLayer.

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

### Se även

* class [ColorBalanceAdjustmentLayer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* hopsättning [Aspose.PSD](../../../)


