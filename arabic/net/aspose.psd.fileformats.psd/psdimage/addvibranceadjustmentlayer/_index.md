---
title: PsdImage.AddVibranceAdjustmentLayer
second_title: Aspose.PSD لمرجع .NET API
description: PsdImage طريقة. يضيف طبقة ضبط Vibrance .
type: docs
weight: 430
url: /ar/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
## PsdImage.AddVibranceAdjustmentLayer method

يضيف طبقة ضبط Vibrance .

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### قيمة الإرجاع

طبقة Vibrance تم إنشاؤها حديثًا.

### أمثلة

يوضح مثال الكود التالي دعم طبقة VibranceLayer والقدرة على تحرير هذا الضبط.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // إنشاء طبقة Vibrance جديدة
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### أنظر أيضا

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)


