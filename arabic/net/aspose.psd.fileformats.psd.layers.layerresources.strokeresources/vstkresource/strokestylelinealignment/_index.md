---
title: VstkResource.StrokeStyleLineAlignment
second_title: Aspose.PSD لمرجع .NET API
description: VstkResource ملكية. الحصول على محاذاة خط نمط الحد أو تعيينها.
type: docs
weight: 100
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
## VstkResource.StrokeStyleLineAlignment property

الحصول على محاذاة خط نمط الحد أو تعيينها.

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
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

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* المجسم [Aspose.PSD](../../../)


