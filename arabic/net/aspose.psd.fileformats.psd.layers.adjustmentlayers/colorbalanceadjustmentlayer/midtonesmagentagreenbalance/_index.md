---
title: "ColorBalanceAdjustmentLayer.MidtonesMagentaGreenBalance"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية ColorBalanceAdjustmentLayer. يحصل أو يضبط توازن المتوسطات الأرجواني الأخضر"
type: docs
weight: 50
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesmagentagreenbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.MidtonesMagentaGreenBalance property

يحصل أو يضبط توازن النغمات المتوسطة للماجنتا الأخضر.

```csharp
public short MidtonesMagentaGreenBalance { get; set; }
```

### Property Value

توازن المتوسطات الأرجواني الأخضر.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | يجب أن يكون توازن المتوسطات الأرجواني الأخضر في النطاق من -100 إلى +100. |

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


