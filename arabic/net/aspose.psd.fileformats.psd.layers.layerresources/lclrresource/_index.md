---
title: "الفئة LclrResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource. الفئة LclrResource. هذا المورد يحتوي على معلومات حول لون الطبقة في قائمة الطبقات في PS. هو الوحيد"
type: docs
weight: 2930
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
{{< psd/tize >}}
## LclrResource class

الفئة LclrResource. هذا المورد يحتوي على معلومات حول لون الطبقة في قائمة الطبقات في PS. إنه فقط

```csharp
public class LclrResource : LayerResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | ينشئ مثيلاً جديدًا للفئة `LclrResource`. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | ينشئ مثيلاً جديدًا للفئة `LclrResource`. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | ينشئ مثيلاً جديدًا للفئة `LclrResource`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | يحصل أو يضبط لون الطبقة. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية الدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

## أمثلة

المثال التالي يوضح كيف يمكنك تغيير تمييز لون الورقة في Aspose.PSD (إعداد لون الورقة)

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// في الملف، ألوان تمييز الطبقات بهذا الترتيب
SheetColorHighlightEnum[] sheetColorsArr = new SheetColorHighlightEnum[] {
    SheetColorHighlightEnum.Red,
    SheetColorHighlightEnum.Orange,
    SheetColorHighlightEnum.Yellow,
    SheetColorHighlightEnum.Green,
    SheetColorHighlightEnum.Blue,
    SheetColorHighlightEnum.Violet,
    SheetColorHighlightEnum.Gray,
    SheetColorHighlightEnum.NoColor
};

// يُستخدم لون ورقة الطبقة لتمييز الطبقات بصريًا.
// على سبيل المثال يمكنك تحديث بعض الطبقات في PSD ثم تمييز باللون الطبقة التي تريد جذب الانتباه إليها.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // يجب عكس الألوان
    Array.Reverse(sheetColorsArr);
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
}

void CheckSheetColorsAndRerverse(SheetColorHighlightEnum[] sheetColors, PsdImage img)
{
    int layersCount = img.Layers.Length;
    for (int layerIndex = 0; layerIndex < layersCount; layerIndex++)
    {
        Layer layer = img.Layers[layerIndex];
        LayerResource[] resources = layer.Resources;
        foreach (LayerResource layerResource in resources)
        {
            // المورد lcrl يظهر دائمًا في قائمة موارد ملف PSD.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // عكس ألوان ورقة الأنماط. إعداد تمييز لون الطبقة.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### انظر أيضًا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


