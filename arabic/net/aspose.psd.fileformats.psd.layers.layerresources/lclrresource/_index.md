---
title: Class LclrResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource فصل. Class LclrResource. يحتوي هذا المورد على معلومات حول لون الطبقة في قائمة الطبقات PS. انها only
type: docs
weight: 2620
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
## LclrResource class

Class LclrResource. يحتوي هذا المورد على معلومات حول لون الطبقة في قائمة الطبقات PS. انها only

```csharp
public class LclrResource : LayerResource
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | يقوم بتهيئة مثيل جديد لملف`LclrResource` فئة . |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | يقوم بتهيئة مثيل جديد لملف`LclrResource` فئة . |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | يقوم بتهيئة مثيل جديد لملف`LclrResource` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | الحصول على لون الطبقة أو تحديده . |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | الحصول على طول مورد الطبقة بالبايت. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/psdversion/) { get; } | يحصل على نسخة مديرية الأمن العام . |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/signature/) { get; } | يحصل على التوقيع. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية التدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع أString الذي يمثل هذا المثال. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

### أمثلة

يوضح المثال التالي كيف يمكنك تغيير تمييز لون الورقة في Aspose.PSD (إعداد لون الورقة)

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// في ملف ألوان تمييز الطبقات بالترتيب
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

// لون ورقة الطبقة يُستخدم لتمييز الطبقات بصريًا. 
// على سبيل المثال ، يمكنك تحديث بعض الطبقات في PSD ثم تمييز الطبقة التي تريد جذب الانتباه إليها من خلال تلوينها.
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
            // يعرض مورد lcrl دائمًا في قائمة موارد ملف psd.
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

### أنظر أيضا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* المجسم [Aspose.PSD](../../)


