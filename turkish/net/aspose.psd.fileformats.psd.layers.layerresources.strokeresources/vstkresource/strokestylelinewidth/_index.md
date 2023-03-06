---
title: VstkResource.StrokeStyleLineWidth
second_title: Aspose.PSD for .NET API Referansı
description: VstkResource mülk. Kontur çizgisi genişliğini alır veya ayarlar.
type: docs
weight: 160
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
## VstkResource.StrokeStyleLineWidth property

Kontur çizgisi genişliğini alır veya ayarlar.

```csharp
public double StrokeStyleLineWidth { get; set; }
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

* class [VstkResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* toplantı [Aspose.PSD](../../../)


