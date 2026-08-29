---
title: "ColorBalanceAdjustmentLayer.MidtonesMagentaGreenBalance"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ColorBalanceAdjustmentLayer-Eigenschaft. Ruft die Mitten-Magenta-Grün-Balance ab oder legt sie fest."
type: docs
weight: 50
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesmagentagreenbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.MidtonesMagentaGreenBalance property

Ruft den Mitten‑Magenta‑Grün‑Ausgleich ab oder legt ihn fest.

```csharp
public short MidtonesMagentaGreenBalance { get; set; }
```

### Property Value

Die Mitten-Magenta-Grün-Balance.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | Mitten-Magenta-Grün-Balance muss im Bereich von -100 bis +100 liegen. |

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


