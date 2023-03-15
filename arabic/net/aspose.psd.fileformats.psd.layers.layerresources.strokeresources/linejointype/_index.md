---
title: Enum LineJoinType
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType تعداد. نوع ربط الخط .
type: docs
weight: 3050
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

نوع ربط الخط .

```csharp
public enum LineJoinType : short
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| BevelJoin | `0` | نوع الصلة Bevel . |
| RoundJoin | `1` | نوع الانضمام Rounnd . |
| MiterJoin | `2` | نوع الانضمام ميتري . |

### أمثلة

يوضح التعليمة البرمجية التالية دعم مورد VstkResource.

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

### أنظر أيضا

* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* المجسم [Aspose.PSD](../../)


