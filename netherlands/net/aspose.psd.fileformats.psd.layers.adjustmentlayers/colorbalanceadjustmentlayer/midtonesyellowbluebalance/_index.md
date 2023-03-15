---
title: ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance
second_title: Aspose.PSD voor .NET API-referentie
description: ColorBalanceAdjustmentLayer eigendom. Krijgt of stelt de Middentonen Geel Blauw Balans in.
type: docs
weight: 60
url: /nl/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesyellowbluebalance/
---
## ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance property

Krijgt of stelt de Middentonen Geel Blauw Balans in.

```csharp
public short MidtonesYellowBlueBalance { get; set; }
```

### Eigendoms-waarde

De middentonen Geel Blauw Balans.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | Middentonen Geel Blauw Balans moet tussen -100 en +100 liggen. |

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


