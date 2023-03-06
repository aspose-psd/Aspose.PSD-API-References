---
title: ColorBalanceAdjustmentLayer.HighlightsMagentaGreenBalance
second_title: Aspose.PSD voor .NET API-referentie
description: ColorBalanceAdjustmentLayer eigendom. Haalt of stelt de Magenta Groenbalans Hooglichten in.
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/highlightsmagentagreenbalance/
---
## ColorBalanceAdjustmentLayer.HighlightsMagentaGreenBalance property

Haalt of stelt de Magenta Groenbalans Hooglichten in.

```csharp
public short HighlightsMagentaGreenBalance { get; set; }
```

### Eigendoms-waarde

De hoogtepunten Magenta groenbalans.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | Highlights Magenta Groen Balans moet tussen -100 en +100 liggen. |

### Voorbeelden

De volgende code demonstreert ondersteuning voor de ColorBalanceAdjustmentLayer.

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

### Zie ook

* class [ColorBalanceAdjustmentLayer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* montage [Aspose.PSD](../../../)


