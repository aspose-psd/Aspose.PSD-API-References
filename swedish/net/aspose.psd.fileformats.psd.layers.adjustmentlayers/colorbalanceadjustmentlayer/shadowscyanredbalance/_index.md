---
title: "ColorBalanceAdjustmentLayer.ShadowsCyanRedBalance"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ColorBalanceAdjustmentLayer property. Gets or sets the Shadows Cyan Red Balance"
type: docs
weight: 80
url: /sv/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowscyanredbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.ShadowsCyanRedBalance property

Hämtar eller anger Skuggornas Cyan Röda Balans.

```csharp
public short ShadowsCyanRedBalance { get; set; }
```

### Property Value

Den Shadows Cyan Red Balance.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Shadows Cyan Red Balance måste vara i intervallet från -100 till +100. |

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


