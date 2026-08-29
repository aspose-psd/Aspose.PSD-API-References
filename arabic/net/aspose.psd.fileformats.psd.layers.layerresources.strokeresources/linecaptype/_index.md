---
title: "تعداد LineCapType"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType enum. نوع طرف الخط"
type: docs
weight: 3400
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
{{< psd/tize >}}
## LineCapType enumeration

نوع نهاية الخط.

```csharp
public enum LineCapType : short
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| RoundCap | `0` | نوع الطرف المستدير. |
| SquareCap | `1` | نوع الطرف المربع. |
| ButtCap | `2` | نوع الطرف المسطح. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


