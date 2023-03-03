---
title: PsdImage.AddInvertAdjustmentLayer
second_title: Aspose.PSD لمرجع .NET API
description: PsdImage طريقة. يضيف طبقة ضبط انعكاس .
type: docs
weight: 360
url: /ar/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
## PsdImage.AddInvertAdjustmentLayer method

يضيف طبقة ضبط انعكاس .

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### قيمة الإرجاع

الطبقة المقلوبة التي تم إنشاؤها

### أمثلة

يوضح الكود التالي دعم InvertAdjustmentLayer وكيفية إضافة InvertAdjustmentLayer.

```csharp
[C#]

var filePath = "InvertStripes_before.psd";
var outputPath = "InvertStripes_after.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    im.AddInvertAdjustmentLayer();
    im.Save(outputPath);
}
```

### أنظر أيضا

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* المجسم [Aspose.PSD](../../../)


