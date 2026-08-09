---
title: "ISmartFilterRenderer.Render"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة ISmartFilterRenderer. تُظهر الفلتر الذكي الحالي على بيانات البكسلات"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/render/
---
{{< psd/tize >}}
## ISmartFilterRenderer.Render method

يقوم بتصيير المرشح الذكي الحالي على بيانات البكسلات.

```csharp
public PixelsData Render(PixelsData pixelsData)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pixelsData | PixelsData | بيانات البكسلات. |

### قيمة الإرجاع

يرجع بيانات البكسلات المعالجة.

## أمثلة

الكود التالي يوضح لك كيفية إنشاء مرشح ذكي مخصص يمتلك مصيّرًا مخصصًا.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // يُهيئ المرشح الذكي غير المدعوم 'Crystallize' في مصفوفة الإدخال
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // معرّف المرشح الذكي 'Crystallize'.
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

        // تطبيق المرشح على SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // تطبيق المرشح على قناع الطبقة
        smartFilter.ApplyToMask(maskLayer);

        //تطبيق المرشح على الطبقة
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
        // معرّف المرشح الذكي 'Crystallize'.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // احصل على بنية المرشح
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // احصل على قيمة حجم Crystallize
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

### انظر أيضًا

* class [PixelsData](../../../aspose.psd/pixelsdata/)
* interface [ISmartFilterRenderer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering](../../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/)
* assembly [Aspose.PSD](../../../)


