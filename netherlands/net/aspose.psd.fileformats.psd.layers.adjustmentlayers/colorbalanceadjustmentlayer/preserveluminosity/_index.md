---
title: ColorBalanceAdjustmentLayer.PreserveLuminosity
second_title: Aspose.PSD voor .NET API-referentie
description: ColorBalanceAdjustmentLayer eigendom. Haalt of stelt een waarde in die aangeeft of ditBlncResource behoudt helderheid.
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

Haalt of stelt een waarde in die aangeeft of dit[`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) behoudt helderheid.

```csharp
public bool PreserveLuminosity { get; set; }
```

### Eigendoms-waarde

`WAAR` als het de helderheid behoudt; anders,`vals` .

### Voorbeelden

De volgende code demonstreert ondersteuning voor de ColorBalanceAdjustmentLayer.

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

### Zie ook

* class [ColorBalanceAdjustmentLayer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* montage [Aspose.PSD](../../../)


