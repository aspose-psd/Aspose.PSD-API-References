---
title: BlackWhiteAdjustmentLayer.UseTint
second_title: Aspose.PSD لمرجع .NET API
description: BlackWhiteAdjustmentLayer ملكية. الحصول على أو تعيين قيمة تشير إلى ما إذا كان لون الصبغة مستخدمًا .
type: docs
weight: 120
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
## BlackWhiteAdjustmentLayer.UseTint property

الحصول على أو تعيين قيمة تشير إلى ما إذا كان [لون الصبغة] مستخدمًا .

```csharp
public bool UseTint { get; set; }
```

### Property_Value

`حقيقي` إذا تم استخدامه [لون خفيف] ؛ خلاف ذلك،`خطأ شنيع` .

### أمثلة

يوضح المثال التالي كيف يمكنك التعامل مع خصائص طبقة ضبط أسود أبيض في Aspose.PSD

```csharp
[C#]

sourceFileName = "BlackWhiteAdjustmentLayerStripesMask.psd";
outputFileName = "OutputBlackWhiteAdjustmentLayerStripesMask.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    var blwhLayer = (BlackWhiteAdjustmentLayer)image.Layers[1];

    blwhLayer.Reds = 15;
    blwhLayer.Yellows = 25;
    blwhLayer.Greens = 35;
    blwhLayer.Cyans = 10;
    blwhLayer.Blues = 50;
    blwhLayer.Magentas = 105;
    blwhLayer.UseTint = true;
    blwhLayer.BwPresetKind = 4;
    blwhLayer.BlackAndWhitePresetFileName = "bwPresetFileName";
    blwhLayer.TintColorRed = 60;
    blwhLayer.TintColorGreen = 80;
    blwhLayer.TintColorBlue = 200;

    image.Save(outputFileName, new PsdOptions());
}
```

### أنظر أيضا

* class [BlackWhiteAdjustmentLayer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* المجسم [Aspose.PSD](../../../)


