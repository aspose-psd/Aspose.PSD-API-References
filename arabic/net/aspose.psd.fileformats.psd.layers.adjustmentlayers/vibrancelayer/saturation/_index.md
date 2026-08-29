---
title: "VibranceLayer.Saturation"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية VibranceLayer. تحصل أو تعيين قيمة التشبع"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
{{< psd/tize >}}
## VibranceLayer.Saturation property

الحصول أو تعيين التشبع.

```csharp
public int Saturation { get; set; }
```

### Property Value

التشبع.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | يجب أن يكون التشبع في النطاق من -100 إلى +100 |

## أمثلة

مثال الشيفرة التالي يوضح دعم طبقة VibranceLayer والقدرة على تعديل هذا الضبط.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // إنشاء VibranceLayer جديد
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### انظر أيضًا

* class [VibranceLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


