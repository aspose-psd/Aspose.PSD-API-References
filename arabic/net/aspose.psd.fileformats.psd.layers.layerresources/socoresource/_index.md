---
title: Class SoCoResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoCoResource فصل. Class SoCoResource. يحتوي هذا المورد على معلومات حول Color Fill Layers
type: docs
weight: 3010
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
## SoCoResource class

Class SoCoResource. يحتوي هذا المورد على معلومات حول Color Fill Layers

```csharp
public class SoCoResource : FillLayerResource
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [SoCoResource](socoresource/)() | يقوم بتهيئة مثيل جديد لملف`SoCoResource` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/) { get; set; } | يحصل على لون RGB . |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length/) { get; } | الحصول على طول مورد الطبقة بالبايت. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/psdversion/) { get; } | يحصل على الحد الأدنى من إصدار psd المطلوب لمورد الطبقة. 0 يشير إلى عدم وجود قيود. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/signature/) { get; } | يحصل على توقيع مورد الطبقة. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية التدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع أString الذي يمثل هذا المثال. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

### أمثلة

يوضح المثال التالي كيفية تحرير SoCoResource (Layer Resource for Color Fill Layer)

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// تحميل صورة موجودة في مثيل لفئة PsdImage
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // العثور على FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // العثور على SoCoResource في قائمة موارد الطبقة
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // تعيين خاصية SoCoResource Color
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### أنظر أيضا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* المجسم [Aspose.PSD](../../)


