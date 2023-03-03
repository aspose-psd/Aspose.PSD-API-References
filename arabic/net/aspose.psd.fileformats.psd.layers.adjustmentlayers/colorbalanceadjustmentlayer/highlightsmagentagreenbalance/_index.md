---
title: ColorBalanceAdjustmentLayer.HighlightsMagentaGreenBalance
second_title: Aspose.PSD لمرجع .NET API
description: ColorBalanceAdjustmentLayer ملكية. الحصول على أو تعيين توازن الأخضر الأرجواني المميز .
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/highlightsmagentagreenbalance/
---
## ColorBalanceAdjustmentLayer.HighlightsMagentaGreenBalance property

الحصول على أو تعيين توازن الأخضر الأرجواني المميز .

```csharp
public short HighlightsMagentaGreenBalance { get; set; }
```

### Property_Value

يبرز التوازن الأخضر الأرجواني .

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | التمييز يجب أن يكون الرصيد الأخضر الأرجواني في نطاق من -100 إلى +100 . |

### أمثلة

يوضح الكود التالي دعم ColorBalanceAdjustmentLayer.

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

### أنظر أيضا

* class [ColorBalanceAdjustmentLayer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* المجسم [Aspose.PSD](../../../)


