---
title: Enum LineCapType
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType تعداد. نوع غطاء الخط .
type: docs
weight: 3040
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

نوع غطاء الخط .

```csharp
public enum LineCapType : short
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| RoundCap | `0` | نوع الغطاء المستدير . |
| SquareCap | `1` | نوع الغطاء المربع . |
| ButtCap | `2` | نوع غطاء المؤخرة . |

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


