---
title: BlackWhiteAdjustmentLayer.Magentas
second_title: Aspose.PSD لمرجع .NET API
description: BlackWhiteAdjustmentLayer ملكية. الحصول على أو تحديد قيمة اللون الأرجواني.
type: docs
weight: 60
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/magentas/
---
## BlackWhiteAdjustmentLayer.Magentas property

الحصول على أو تحديد قيمة اللون الأرجواني.

```csharp
public int Magentas { get; set; }
```

### Property_Value

قيمة اللون الأرجواني .

### أمثلة

يوضح المثال التالي كيف يمكنك إضافة طبقة ضبط أسود أبيض في وقت التشغيل في Aspose.PSD

```csharp
[C#]

string sourceFileName = "Stripes.psd";
string outputFileName = "OutputStripes.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    BlackWhiteAdjustmentLayer newLayer = image.AddBlackWhiteAdjustmentLayer();
    newLayer.Name = "BlackWhiteAdjustmentLayer";
    newLayer.Reds = 22;
    newLayer.Yellows = 92;
    newLayer.Greens = 70;
    newLayer.Cyans = 79;
    newLayer.Blues = 7;
    newLayer.Magentas = 28;

    image.Save(outputFileName, new PsdOptions());
}
```

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


