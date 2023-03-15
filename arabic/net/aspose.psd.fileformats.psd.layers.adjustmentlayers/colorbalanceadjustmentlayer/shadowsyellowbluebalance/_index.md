---
title: ColorBalanceAdjustmentLayer.ShadowsYellowBlueBalance
second_title: Aspose.PSD لمرجع .NET API
description: ColorBalanceAdjustmentLayer ملكية. الحصول على أو تعيين توازن الظلال YellowBlue .
type: docs
weight: 100
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowsyellowbluebalance/
---
## ColorBalanceAdjustmentLayer.ShadowsYellowBlueBalance property

الحصول على أو تعيين توازن الظلال YellowBlue .

```csharp
public short ShadowsYellowBlueBalance { get; set; }
```

### Property_Value

توازن الظلال الصفراء الزرقاء .

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | يجب أن يتراوح الرصيد بين الظلال والأصفر والأزرق من -100 إلى +100. |

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


