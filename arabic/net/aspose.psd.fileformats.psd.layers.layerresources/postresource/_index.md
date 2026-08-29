---
title: "الفئة PostResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PostResource. الفئة PostResource. إعدادات طبقة التدرج اللوني"
type: docs
weight: 3300
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/
---
{{< psd/tize >}}
## PostResource class

الفئة PostResource. إعدادات طبقة التحويل إلى ألوان محدودة.

```csharp
public class PostResource : AdjustmentLayerResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PostResource](postresource/)() | الباني الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| [Levels](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/) { get; set; } | مستويات طبقة Posterize. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية الدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

## أمثلة

الكود التالي يوضح القدرة على معالجة PostResource.

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];

    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is PostResource)
        {
            ((PostResource)resource).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### انظر أيضًا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


