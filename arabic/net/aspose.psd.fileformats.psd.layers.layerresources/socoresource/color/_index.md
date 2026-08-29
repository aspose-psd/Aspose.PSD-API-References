---
title: "SoCoResource.Color"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "SoCoResource خاصية. يحصل على اللون RGB"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
{{< psd/tize >}}
## SoCoResource.Color property

يحصل على لون RGB.

```csharp
public Color Color { get; set; }
```

### قيمة الإرجاع

لون RGB

## أمثلة

المثال التالي يوضح كيفية تحرير SoCoResource (مورد الطبقة لطبقة تعبئة اللون)

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// حمّل صورة موجودة إلى مثال من فئة PsdImage
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

                    // تعيين خاصية اللون في SoCoResource
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

### انظر أيضًا

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


