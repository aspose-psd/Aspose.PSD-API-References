---
title: "SharpenSmartFilter.SharpenSmartFilter"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ SharpenSmartFilter. يهيئ نسخة جديدة من الفئة SharpenSmartFilter"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter() {#constructor}

يهيئ نسخة جديدة من الفئة [`SharpenSmartFilter`](../).

```csharp
public SharpenSmartFilter()
```

## أمثلة

الكود التالي يوضح دعم SharpenSmartFilter.

```csharp
[C#]

string sourceFile = "sharpen_source.psd";
string outputPsd = "sharpen_output.psd";
string outputPng = "sharpen_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFile))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // تحرير الفلاتر الذكية
    SharpenSmartFilter sharpen = (SharpenSmartFilter)smartObj.SmartFilters.Filters[0];

    // تحقق من قيم الفلتر
    AssertAreEqual(BlendMode.Normal, sharpen.BlendMode);
    AssertAreEqual(100d, sharpen.Opacity);
    AssertAreEqual(true, sharpen.IsEnabled);

    // تحديث قيم الفلتر
    sharpen.BlendMode = BlendMode.Divide;
    sharpen.Opacity = 75;
    sharpen.IsEnabled = false;

    // إضافة عناصر فلتر جديدة
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new SharpenSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // تطبيق التغييرات
    smartObj.SmartFilters.UpdateResourceValues();
    smartObj.UpdateModifiedContent();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### انظر أيضًا

* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)

---

## SharpenSmartFilter(DescriptorStructure) {#constructor_1}

يهيئ نسخة جديدة من الفئة [`SharpenSmartFilter`](../).

```csharp
public SharpenSmartFilter(DescriptorStructure sourceDescriptor)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceDescriptor | DescriptorStructure | هيكل الوصف مع معلومات الفلتر الذكي. |

### انظر أيضًا

* class [DescriptorStructure](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/)
* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)


