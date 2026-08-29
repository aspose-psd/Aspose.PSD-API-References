---
title: "LclrResource.Color"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية LclrResource. الحصول أو تعيين لون الطبقة"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/
---
{{< psd/tize >}}
## LclrResource.Color property

يحصل أو يضبط لون الطبقة.

```csharp
public SheetColorHighlightEnum Color { get; set; }
```

### Property Value

اللون.

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

* enum [SheetColorHighlightEnum](../../sheetcolorhighlightenum/)
* class [LclrResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


