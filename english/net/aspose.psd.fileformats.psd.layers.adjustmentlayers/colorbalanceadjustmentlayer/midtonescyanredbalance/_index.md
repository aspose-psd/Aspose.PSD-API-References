---
title: ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance
second_title: Aspose.PSD for .NET API Reference
description: ColorBalanceAdjustmentLayer property. Gets or sets the Midtones Cyan Red Balance
type: docs
weight: 40
url: /net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonescyanredbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance property

Gets or sets the Midtones Cyan Red Balance.

```csharp
public short MidtonesCyanRedBalance { get; set; }
```

### Property Value

The Midtones Cyan Red Balance.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Midtones Cyan Red Balance must be in range from -100 to +100. |

## Examples

The following code demonstrates support for the ColorBalanceAdjustmentLayer.

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

### See Also

* class [ColorBalanceAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


