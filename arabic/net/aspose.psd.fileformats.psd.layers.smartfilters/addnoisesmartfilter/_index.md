---
title: Class AddNoiseSmartFilter
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.AddNoiseSmartFilter فصل. عامل التصفية الذكي AddNoise .
type: docs
weight: 3420
url: /ar/net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/
---
## AddNoiseSmartFilter class

عامل التصفية الذكي AddNoise .

```csharp
public sealed class AddNoiseSmartFilter : SmartFilter
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [AddNoiseSmartFilter](addnoisesmartfilter/)() | يقوم بتهيئة مثيل جديد لملف`AddNoiseSmartFilter` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AmountNoise](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/amountnoise/) { get; set; } | الحصول على أو تعيين مقدار قيمة الضوضاء. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | الحصول على أو تحديد وضع المزج . |
| [Distribution](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/distribution/) { get; set; } | الحصول على أو تحديد توزيع مرشح الضوضاء. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/filterid/) { get; } | يحصل على معرف نوع المرشح الذكي. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | الحصول على أو تعيين حالة تمكين عامل التصفية الذكي. |
| [IsMonochromatic](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/ismonochromatic/) { get; set; } | الحصول على أو تحديد قيمة أحادية اللون. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/name/) { get; } | الحصول على اسم المرشح الذكي . |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | الحصول على أو تعيين قيمة عتامة المرشح الذكي. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | هيكل واصف المصدر ببيانات التصفية الذكية. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | يطبق عامل التصفية الحالي على الإدخال[`RasterImage`](../../aspose.psd/rasterimage/) الصورة . |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | يطبق عامل التصفية الحالي على الإدخال[`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) قناع البيانات. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | يجعل استنساخ العضو للمثيل الحالي من النوع. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/filtertype/) | معرّف المرشح الذكي الحالي. |

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

* class [SmartFilter](../smartfilter/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* المجسم [Aspose.PSD](../../)


