---
title: "ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα ColorBalanceAdjustmentLayer. Λαμβάνει ή ορίζει το Midtones Cyan Red Balance"
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonescyanredbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance property

Λαμβάνει ή ορίζει το Midtones Cyan Red Balance.

```csharp
public short MidtonesCyanRedBalance { get; set; }
```

### Property Value

Το Midtones Cyan Red Balance.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | Το Midtones Cyan Red Balance πρέπει να είναι στο εύρος από -100 έως +100. |

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


