---
title: VstkResource.StrokeStyleLineWidth
second_title: Aspose.PSD لمرجع .NET API
description: VstkResource ملكية. الحصول على أو تعيين عرض خط الحد .
type: docs
weight: 160
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
## VstkResource.StrokeStyleLineWidth property

الحصول على أو تعيين عرض خط الحد .

```csharp
public double StrokeStyleLineWidth { get; set; }
```

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

* class [VstkResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* المجسم [Aspose.PSD](../../../)


