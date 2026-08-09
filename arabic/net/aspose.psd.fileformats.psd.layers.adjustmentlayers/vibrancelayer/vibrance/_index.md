---
title: "VibranceLayer.Vibrance"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية VibranceLayer. تحصل أو تعيين قيمة الحيوية"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
{{< psd/tize >}}
## VibranceLayer.Vibrance property

الحصول أو تعيين الإشراق.

```csharp
public int Vibrance { get; set; }
```

### Property Value

الحيوية.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | يجب أن تكون الحيوية في النطاق من -180 إلى +180 |

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


