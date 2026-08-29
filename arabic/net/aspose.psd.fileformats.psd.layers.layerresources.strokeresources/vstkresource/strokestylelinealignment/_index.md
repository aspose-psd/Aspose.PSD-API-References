---
title: "VstkResource.StrokeStyleLineAlignment"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية VstkResource. تحصل أو تعيين محاذاة خط نمط الحد"
type: docs
weight: 80
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
{{< psd/tize >}}
## VstkResource.StrokeStyleLineAlignment property

يحصل أو يضبط محاذاة خط نمط الخط.

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
```

## أمثلة

الكود التالي يوضح دعم مورد VstkResource.

```csharp
[C#]

string srcFile = "StrokeShapeTest1.psd";
string dstFile = "StrokeShapeTest2.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    Layer layer = image.Layers[1];
    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is VstkResource)
        {
            VstkResource vstkResource = (VstkResource)resource;
            vstkResource.StrokeStyleLineAlignment = StrokePosition.Outside;
            vstkResource.StrokeStyleLineWidth = 20;
        }
    }

    image.Save(dstFile);
}
```

### انظر أيضًا

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


