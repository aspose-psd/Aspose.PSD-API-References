---
title: AddNoiseSmartFilter.Distribution
second_title: Aspose.PSD لمرجع .NET API
description: AddNoiseSmartFilter ملكية. الحصول على أو تحديد توزيع مرشح الضوضاء.
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/distribution/
---
## AddNoiseSmartFilter.Distribution property

الحصول على أو تحديد توزيع مرشح الضوضاء.

```csharp
public NoiseDistribution Distribution { get; set; }
```

### أمثلة

يوضح هذا المثال دعم واجهة المرشحات الذكية.

```csharp
[C#]

string sourceFilte = "r2_SmartFilters.psd";
string outputPsd = "out_r2_SmartFilters.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFilte))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // تحرير المرشحات الذكية
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // تحقق من قيم التصفية
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // تحديث قيم عامل التصفية
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // إضافة عناصر تصفية جديدة
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // تطبيق التغييرات
    smartObj.SmartFilters.UpdateResourceValues();

    // تطبيق المرشحات
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // تحقق من قيم التصفية
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### أنظر أيضا

* enum [NoiseDistribution](../../noisedistribution/)
* class [AddNoiseSmartFilter](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../addnoisesmartfilter/)
* المجسم [Aspose.PSD](../../../)


