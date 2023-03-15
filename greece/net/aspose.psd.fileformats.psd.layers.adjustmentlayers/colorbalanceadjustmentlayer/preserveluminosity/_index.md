---
title: ColorBalanceAdjustmentLayer.PreserveLuminosity
second_title: Aspose.PSD για Αναφορά API .NET
description: ColorBalanceAdjustmentLayer ιδιοκτησία. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτόBlncResource διατηρεί τη φωτεινότητα.
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό[`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) διατηρεί τη φωτεινότητα.

```csharp
public bool PreserveLuminosity { get; set; }
```

### Αξία περιουσίας

`αληθής` αν διατηρεί τη φωτεινότητα? σε διαφορετική περίπτωση,`ψευδής` .

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


