---
title: ColorBalanceAdjustmentLayer.ShadowsCyanRedBalance
second_title: Aspose.PSD für .NET-API-Referenz
description: ColorBalanceAdjustmentLayer eigendom. Ruft die SchattenCyanRotBalance ab oder legt sie fest.
type: docs
weight: 80
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowscyanredbalance/
---
## ColorBalanceAdjustmentLayer.ShadowsCyanRedBalance property

Ruft die Schatten-Cyan-Rot-Balance ab oder legt sie fest.

```csharp
public short ShadowsCyanRedBalance { get; set; }
```

### Eigentumswert

The Shadows Cyan Red Balance.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | Shadows Cyan Red Balance muss im Bereich von -100 bis +100 liegen. |

### Beispiele

Der folgende Code demonstriert die Unterstützung für ColorBalanceAdjustmentLayer.

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

### Siehe auch

* class [ColorBalanceAdjustmentLayer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* Montage [Aspose.PSD](../../../)


