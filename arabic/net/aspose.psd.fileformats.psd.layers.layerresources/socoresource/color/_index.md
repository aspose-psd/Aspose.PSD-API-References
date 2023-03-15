---
title: SoCoResource.Color
second_title: Aspose.PSD لمرجع .NET API
description: SoCoResource ملكية. يحصل على لون RGB .
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
## SoCoResource.Color property

يحصل على لون RGB .

```csharp
public Color Color { get; set; }
```

### قيمة الإرجاع

لون RGB

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

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../socoresource/)
* المجسم [Aspose.PSD](../../../)


