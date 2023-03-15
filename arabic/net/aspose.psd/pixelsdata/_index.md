---
title: Class PixelsData
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.PixelsData فصل. فئة تخزين بيانات بكسل الصورة وحدودها.
type: docs
weight: 5250
url: /ar/net/aspose.psd/pixelsdata/
---
## PixelsData class

فئة تخزين بيانات بكسل الصورة وحدودها.

```csharp
public sealed class PixelsData
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PixelsData](pixelsdata/#constructor)() | يقوم بتهيئة مثيل جديد لملف`PixelsData` فئة . |
| [PixelsData](pixelsdata/#constructor_1)(int[], Rectangle) | يقوم بتهيئة مثيل جديد لملف`PixelsData` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds/) { get; set; } | الحصول على أو تعيين حدود بيانات البكسل . |
| [Pixels](../../aspose.psd/pixelsdata/pixels/) { get; set; } | الحصول على أو تعيين بيانات البكسل . |

### أمثلة

يوضح لك الكود التالي كيفية إنشاء عامل تصفية ذكي مخصص به عارض مخصص.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // يدخل المرشح الذكي "التبلور" غير المدعوم في صفيف الإدخال
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // معرّف الفلتر الذكي "Crystallize".
        int id = 1131574132;

        for (int i = 0; i < smartFilters.Length; i++)
        {
            var smartFilter = smartFilters[i];
            if (smartFilter is UnknownSmartFilter && smartFilter.FilterId == id)
            {
                var customSmartFilterInstance = new CustomSmartFilterWithRenderer();
                customSmartFilterInstance.SourceDescriptor.Structures = smartFilter.SourceDescriptor.Structures;
                smartFilters[i] = customSmartFilterInstance;
            }
        }

        return smartFilters;
    }

    using (var image = (PsdImage) Image.Load(sourceFile))
    {
        SmartObjectLayer smartLayer = (SmartObjectLayer) image.Layers[1];
        Layer maskLayer = image.Layers[2];
        Layer regularLayer = image.Layers[3];

        smartLayer.SmartFilters.Filters = InitUnknownSmartFilters(smartLayer.SmartFilters.Filters);
        var smartFilter = smartLayer.SmartFilters.Filters[0];

        // تطبيق عامل التصفية على SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // تطبيق مرشح على قناع الطبقة
        smartFilter.ApplyToMask(maskLayer);

        // تطبيق مرشح على طبقة
        smartFilter.Apply(regularLayer);

        image.Save(outputPsd);
        image.Save(outputPng, new PngOptions());
    }
}

public sealed class CustomSmartFilterWithRenderer : SmartFilter, ISmartFilterRenderer
{
    public override string Name
    {
        get { return "Custom 'Crystallize' smart filter\0"; }
    }

    public override int FilterId
    {
        // معرّف الفلتر الذكي "Crystallize".
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // الحصول على هيكل المرشح
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // الحصول على قيمة حجم التبلور
        var valueStructure = (IntegerStructure) filterDescriptor.Structures[0];

        for (int i = 0; i < pixelsData.Pixels.Length; i++)
        {
            if (i % valueStructure.Value == 0)
            {
                pixelsData.Pixels[i] = 0;
            }
        }

        return pixelsData;
    }
}
```

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


