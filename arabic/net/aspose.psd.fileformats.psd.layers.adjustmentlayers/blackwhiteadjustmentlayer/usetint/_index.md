---
title: "BlackWhiteAdjustmentLayer.UseTint"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية BlackWhiteAdjustmentLayer. يحصل أو يضبط قيمة تشير إلى ما إذا كان tint color مستخدمًا"
type: docs
weight: 120
url: /ar/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.UseTint property

يحصل أو يضبط قيمة تشير إلى ما إذا كان [tint color] مستخدمًا.

```csharp
public bool UseTint { get; set; }
```

### Property Value

`true` إذا تم استخدام [tint color]؛ وإلا `false`.

## أمثلة

المثال التالي يوضح كيف يمكنك تعديل خصائص طبقة تعديل الأبيض والأسود في Aspose.PSD

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

### انظر أيضًا

* class [BlackWhiteAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


