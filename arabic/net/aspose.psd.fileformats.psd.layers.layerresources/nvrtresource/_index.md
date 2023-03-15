---
title: Class NvrtResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.NvrtResource فصل. فئة NvrtResource. مورد طبقة التعديل المقلوبة.
type: docs
weight: 2840
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---
## NvrtResource class

فئة NvrtResource. مورد طبقة التعديل المقلوبة.

```csharp
public class NvrtResource : AdjustmentLayerResource
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [NvrtResource](nvrtresource/#constructor)() | يقوم بتهيئة مثيل جديد لملف`NvrtResource` فئة . |
| [NvrtResource](nvrtresource/#constructor_1)(byte[]) | يقوم بتهيئة مثيل جديد لملف`NvrtResource` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/length/) { get; } | الحصول على طول مورد الطبقة بالبايت. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/psdversion/) { get; } | الحصول على إصدار PSD . |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | يحصل على التوقيع. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية التدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع أString الذي يمثل هذا المثال. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/typetoolkey/) | مفتاح معلومات أداة الكتابة. |

### أمثلة

يوضح المثال التالي كيفية الحصول على NvrtResource.

```csharp
[C#]

string sourceFilePath = "InvertAdjustmentLayer.psd";
NvrtResource resource = null;
using (PsdImage psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    foreach (Aspose.PSD.FileFormats.Psd.Layers.Layer layer in psdImage.Layers)
    {
        if (layer is InvertAdjustmentLayer)
        {
            foreach (Aspose.PSD.FileFormats.Psd.Layers.LayerResource layerResource in layer.Resources)
            {
                if (layerResource is NvrtResource)
                {
                    // يتم دعم NvrtResource.
                    resource = (NvrtResource)layerResource;
                    break;
                }
            }
        }
    }
}
```

### أنظر أيضا

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* المجسم [Aspose.PSD](../../)


