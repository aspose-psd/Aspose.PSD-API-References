---
title: "ColorBalanceAdjustmentLayer.PreserveLuminosity"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα ColorBalanceAdjustmentLayer. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το BlncResource διατηρεί τη φωτεινότητα"
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) διατηρεί τη φωτεινότητα.

```csharp
public bool PreserveLuminosity { get; set; }
```

### Property Value

`true` εάν διατηρεί τη φωτεινότητα· διαφορετικά, `false`.

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


