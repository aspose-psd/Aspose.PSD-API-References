---
title: "ColorBalanceAdjustmentLayer.HighlightsCyanRedBalance"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα ColorBalanceAdjustmentLayer. Λαμβάνει ή ορίζει το Highlights Cyan Red Balance"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/highlightscyanredbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.HighlightsCyanRedBalance property

Λαμβάνει ή ορίζει το Highlights Cyan Red Balance.

```csharp
public short HighlightsCyanRedBalance { get; set; }
```

### Property Value

Το Highlights Cyan Red Balance.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | Το Highlights Cyan Red Balance πρέπει να βρίσκεται στο εύρος από -100 έως +100. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη για το ColorBalanceAdjustmentLayer.

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

### Δείτε επίσης

* class [ColorBalanceAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


