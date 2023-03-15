---
title: ColorBalanceAdjustmentLayer.MidtonesMagentaGreenBalance
second_title: Aspose.PSD για Αναφορά API .NET
description: ColorBalanceAdjustmentLayer ιδιοκτησία. Λαμβάνει ή ρυθμίζει το Midtones Magenta Green Balance.
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesmagentagreenbalance/
---
## ColorBalanceAdjustmentLayer.MidtonesMagentaGreenBalance property

Λαμβάνει ή ρυθμίζει το Midtones Magenta Green Balance.

```csharp
public short MidtonesMagentaGreenBalance { get; set; }
```

### Αξία περιουσίας

The Midtones Magenta Green Balance.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentOutOfRangeException | Midtones Magenta Green Balance πρέπει να κυμαίνεται από -100 έως +100. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει υποστήριξη για το ColorBalanceAdjustmentLayer.

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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* συνέλευση [Aspose.PSD](../../../)


