---
title: "ColorBalanceAdjustmentLayer.PreserveLuminosity"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية ColorBalanceAdjustmentLayer. يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا BlncResource يحافظ على الإضاءة"
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا [`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) يحافظ على الإضاءة.

```csharp
public bool PreserveLuminosity { get; set; }
```

### Property Value

`true` إذا كان يحافظ على الإضاءة؛ وإلا `false`.

## أمثلة

الكود التالي يوضح دعم طبقة ColorBalanceAdjustmentLayer.

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

### انظر أيضًا

* class [ColorBalanceAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


