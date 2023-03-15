---
title: VstkResource.StrokeStyleLineAlignment
second_title: Aspose.PSD for .NET API Referansı
description: VstkResource mülk. Kontur stili çizgi hizalamasını alır veya ayarlar.
type: docs
weight: 100
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
## VstkResource.StrokeStyleLineAlignment property

Kontur stili çizgi hizalamasını alır veya ayarlar.

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
```

### Örnekler

Aşağıdaki kod, VstkResource kaynağının desteğini gösterir.

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

### Ayrıca bakınız

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* toplantı [Aspose.PSD](../../../)


