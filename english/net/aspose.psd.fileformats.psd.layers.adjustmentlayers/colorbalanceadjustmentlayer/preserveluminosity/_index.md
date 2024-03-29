---
title: ColorBalanceAdjustmentLayer.PreserveLuminosity
second_title: Aspose.PSD for .NET API Reference
description: ColorBalanceAdjustmentLayer property. Gets or sets a value indicating whether this BlncResource preserves luminosity
type: docs
weight: 70
url: /net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

Gets or sets a value indicating whether this [`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) preserves luminosity.

```csharp
public bool PreserveLuminosity { get; set; }
```

### Property Value

`true` if it preserves luminosity; otherwise, `false`.

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


