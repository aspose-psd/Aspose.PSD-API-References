---
title: "PsdImage.AddVibranceAdjustmentLayer"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة PsdImage. إضافة طبقة تعديل Vibrance"
type: docs
weight: 490
url: /ar/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddVibranceAdjustmentLayer method

يضيف طبقة تعديل الحيوية.

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### قيمة الإرجاع

طبقة Vibrance جديدة تم إنشاؤها.

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


