---
title: BlackWhiteAdjustmentLayer.BlackAndWhitePresetFileName
second_title: Aspose.PSD لمرجع .NET API
description: BlackWhiteAdjustmentLayer ملكية. الحصول على أو تعيين اسم ملف الإعداد المسبق بالأبيض والأسود.
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/blackandwhitepresetfilename/
---
## BlackWhiteAdjustmentLayer.BlackAndWhitePresetFileName property

الحصول على أو تعيين اسم ملف الإعداد المسبق بالأبيض والأسود.

```csharp
public string BlackAndWhitePresetFileName { get; set; }
```

### Property_Value

اسم ملف الإعداد المسبق بالأبيض والأسود .

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


