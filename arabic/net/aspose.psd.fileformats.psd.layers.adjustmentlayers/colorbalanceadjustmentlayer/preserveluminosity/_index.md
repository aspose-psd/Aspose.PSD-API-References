---
title: ColorBalanceAdjustmentLayer.PreserveLuminosity
second_title: Aspose.PSD لمرجع .NET API
description: ColorBalanceAdjustmentLayer ملكية. الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذاBlncResource يحافظ على اللمعان.
type: docs
weight: 70
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا[`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) يحافظ على اللمعان.

```csharp
public bool PreserveLuminosity { get; set; }
```

### Property_Value

`حقيقي` إذا كان يحافظ على اللمعان ؛ خلاف ذلك،`خطأ شنيع` .

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


