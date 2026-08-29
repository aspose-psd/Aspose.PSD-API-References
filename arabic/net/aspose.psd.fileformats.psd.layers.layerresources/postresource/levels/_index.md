---
title: "PostResource.Levels"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية PostResource. مستويات طبقة التدرج اللوني"
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/
---
{{< psd/tize >}}
## PostResource.Levels property

مستويات طبقة Posterize.

```csharp
public short Levels { get; set; }
```

### قيمة الإرجاع

قيمة int للمستويات

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

* class [PostResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


