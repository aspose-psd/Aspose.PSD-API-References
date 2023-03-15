---
title: VibranceLayer.Saturation
second_title: Aspose.PSD لمرجع .NET API
description: VibranceLayer ملكية. الحصول على أو تعيين التشبع.
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
## VibranceLayer.Saturation property

الحصول على أو تعيين التشبع.

```csharp
public int Saturation { get; set; }
```

### Property_Value

التشبع.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | يجب أن يتراوح التشبع من -100 إلى +100 |

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

* class [VibranceLayer](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* المجسم [Aspose.PSD](../../../)


