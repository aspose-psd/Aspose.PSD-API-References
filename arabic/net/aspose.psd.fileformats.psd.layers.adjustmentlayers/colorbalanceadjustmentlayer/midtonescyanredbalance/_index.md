---
title: "ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية ColorBalanceAdjustmentLayer. يحصل أو يضبط توازن المتوسطات السيان الأحمر"
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonescyanredbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance property

يحصل أو يضبط توازن النغمات المتوسطة للسيان الأحمر.

```csharp
public short MidtonesCyanRedBalance { get; set; }
```

### Property Value

توازن المتوسطات السيان الأحمر.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | يجب أن يكون توازن المتوسطات السيان الأحمر في النطاق من -100 إلى +100. |

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


