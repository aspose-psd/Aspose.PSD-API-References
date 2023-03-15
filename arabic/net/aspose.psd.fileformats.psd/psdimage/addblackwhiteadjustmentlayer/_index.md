---
title: PsdImage.AddBlackWhiteAdjustmentLayer
second_title: Aspose.PSD لمرجع .NET API
description: PsdImage طريقة. يضيف طبقة ضبط أسود أبيض.
type: docs
weight: 290
url: /ar/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
## PsdImage.AddBlackWhiteAdjustmentLayer method

يضيف طبقة ضبط أسود أبيض.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### قيمة الإرجاع

طبقة ضبط أسود أبيض تم إنشاؤها.

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

### أنظر أيضا

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)


