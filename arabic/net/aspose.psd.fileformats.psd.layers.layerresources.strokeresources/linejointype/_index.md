---
title: "تعداد LineJoinType"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "تعداد Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType. نوع وصل الخط"
type: docs
weight: 3410
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
{{< psd/tize >}}
## LineJoinType enumeration

نوع وصل الخط.

```csharp
public enum LineJoinType : short
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| BevelJoin | `0` | نوع الوصل المائل. |
| RoundJoin | `1` | نوع الوصل المستدير. |
| MiterJoin | `2` | نوع الوصل المِقْطَع. |

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


