---
title: "PsdImage.AddPosterizeAdjustmentLayer"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة PsdImage. يضيف طبقة تعديل Posterize"
type: docs
weight: 430
url: /ar/net/aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddPosterizeAdjustmentLayer method

يضيف طبقة تعديل تقليل الألوان.

```csharp
public PosterizeLayer AddPosterizeAdjustmentLayer()
```

### قيمة الإرجاع

مثيل PosterizeLayer.

## أمثلة

الكود التالي يوضح القدرة على إضافة PosterizeAdjustmentLayer عبر PsdImage.

```csharp
[C#]

string srcFile = "zendeya.psd";
string outFile = "zendeya.psd.out.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    psdImage.AddPosterizeAdjustmentLayer();
    psdImage.Save(outFile);
}

// تحقق من التغييرات المحفوظة
using (PsdImage image = (PsdImage)Image.Load(
           outFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    AssertAreEqual(2, image.Layers.Length);

    PosterizeLayer posterizeLayer = (PosterizeLayer)image.Layers[1];

    AssertAreEqual(true, posterizeLayer is PosterizeLayer);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### انظر أيضًا

* class [PosterizeLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


