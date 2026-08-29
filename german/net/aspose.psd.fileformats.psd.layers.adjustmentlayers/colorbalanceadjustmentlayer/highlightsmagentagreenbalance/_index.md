---
title: "ColorBalanceAdjustmentLayer.HighlightsMagentaGreenBalance"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ColorBalanceAdjustmentLayer property. Ruft den Highlights Magenta Green Balance ab oder legt ihn fest"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/highlightsmagentagreenbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.HighlightsMagentaGreenBalance property

Ruft den Highlights‑Magenta‑Grün‑Ausgleich ab oder legt ihn fest.

```csharp
public short HighlightsMagentaGreenBalance { get; set; }
```

### Property Value

Der Highlights Magenta Green Balance.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | Highlights Magenta Green Balance muss im Bereich von -100 bis +100 liegen. |

## Beispiele

Der folgende Code demonstriert die Unterstützung für die ColorBalanceAdjustmentLayer.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


