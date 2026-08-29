---
title: "ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ColorBalanceAdjustmentLayer property. Gets or sets the Midtones Yellow Blue Balance"
type: docs
weight: 60
url: /sv/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesyellowbluebalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance property

Hämtar eller anger Mellantonernas Gul Blå Balans.

```csharp
public short MidtonesYellowBlueBalance { get; set; }
```

### Property Value

Den Midtones Yellow Blue Balance.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Midtones Yellow Blue Balance måste vara i intervallet från -100 till +100. |

## Exempel

Följande kod demonstrerar stöd för ColorBalanceAdjustmentLayer.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


