---
title: VibranceLayer.Vibrance
second_title: Aspose.PSD لمرجع .NET API
description: VibranceLayer ملكية. الحصول على الحيوية أو تحديدها .
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
## VibranceLayer.Vibrance property

الحصول على الحيوية أو تحديدها .

```csharp
public int Vibrance { get; set; }
```

### Property_Value

الحيوية.

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentOutOfRangeException | يجب أن تتراوح الحيوية بين -180 و +180 |

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


