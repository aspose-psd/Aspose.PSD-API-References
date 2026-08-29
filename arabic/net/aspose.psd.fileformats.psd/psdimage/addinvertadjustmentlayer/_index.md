---
title: "PsdImage.AddInvertAdjustmentLayer"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة PsdImage. تضيف طبقة تعديل عكسية"
type: docs
weight: 380
url: /ar/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddInvertAdjustmentLayer method

يضيف طبقة تعديل عكس.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### قيمة الإرجاع

الطبقة العكسية التي تم إنشاؤها

## أمثلة

الكود التالي يوضح دعم InvertAdjustmentLayer وكيفية إضافة InvertAdjustmentLayer.

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

### انظر أيضًا

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


