---
title: LclrResource.Color
second_title: Aspose.PSD لمرجع .NET API
description: LclrResource ملكية. الحصول على لون الطبقة أو تحديده .
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/
---
## LclrResource.Color property

الحصول على لون الطبقة أو تحديده .

```csharp
public SheetColorHighlightEnum Color { get; set; }
```

### Property_Value

اللون .

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

* enum [SheetColorHighlightEnum](../../sheetcolorhighlightenum/)
* class [LclrResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../lclrresource/)
* المجسم [Aspose.PSD](../../../)


