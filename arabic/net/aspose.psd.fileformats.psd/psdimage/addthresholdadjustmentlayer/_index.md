---
title: "PsdImage.AddThresholdAdjustmentLayer"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة PsdImage. يضيف طبقة تعديل العتبة"
type: docs
weight: 480
url: /ar/net/aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddThresholdAdjustmentLayer method

يضيف طبقة تعديل العتبة.

```csharp
public ThresholdLayer AddThresholdAdjustmentLayer()
```

### قيمة الإرجاع

طبقة تعديل العتبة التي تم إنشاؤها.

## أمثلة

الكود التالي يوضح دعم طبقة تعديل ThresholdLayer.

```csharp
[C#]

string sourceFileWithThresholdLayer = "flowers_threshold_source.psd";
string outputPsdWithThresholdLayer = "flowers_threshold_output.psd";
string outputPngWithThresholdLayer = "flowers_threshold_output.png";

string sourceFileWithoutThresholdLayer = "flowers_source.psd";
string outputPsdWithoutThresholdLayer = "flowers_output.psd";
string outputPngWithoutThresholdLayer = "flowers_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// احصل، وتحقق، وغير طبقة تعديل Threshold من الصورة.
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // احصل على طبقة تعديل Threshold.
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // تحقق من معلمات الطبقات.
            AssertAreEqual(level, (short)115);

            // اضبط معلمات الطبقات.
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// أضف واضبط طبقة تعديل Threshold إلى الصورة.
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // أضف طبقة تعديل Threshold.
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // اضبط معلمات الطبقات.
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### انظر أيضًا

* class [ThresholdLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


