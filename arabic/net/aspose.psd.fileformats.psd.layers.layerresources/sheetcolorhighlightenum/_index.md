---
title: Enum SheetColorHighlightEnum
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum تعداد. الألوان الممكنة لإعداد لون الورقة. إنه اللون الزخرفي لواجهة المستخدم للطبقة في قائمة الطبقات في PS
type: docs
weight: 2970
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
## SheetColorHighlightEnum enumeration

الألوان الممكنة لإعداد لون الورقة. إنه اللون الزخرفي لواجهة المستخدم للطبقة في قائمة الطبقات في PS

```csharp
public enum SheetColorHighlightEnum : short
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| NoColor | `0` | اللون غير محدد . |
| Red | `1` | اللون الأحمر . |
| Orange | `2` | اللون البرتقالي . |
| Yellow | `3` | اللون الأصفر . |
| Green | `4` | اللون الأخضر . |
| Blue | `5` | اللون الأزرق . |
| Violet | `6` | اللون البنفسجي . |
| Gray | `7` | اللون الرمادي . |

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

* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* المجسم [Aspose.PSD](../../)


