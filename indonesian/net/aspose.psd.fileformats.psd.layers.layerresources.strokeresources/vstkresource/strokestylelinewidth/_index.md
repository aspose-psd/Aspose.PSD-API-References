---
title: VstkResource.StrokeStyleLineWidth
second_title: Aspose.PSD untuk Referensi .NET API
description: VstkResource Properti. Mendapat atau mengatur lebar garis Stroke.
type: docs
weight: 160
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
## VstkResource.StrokeStyleLineWidth property

Mendapat atau mengatur lebar garis Stroke.

```csharp
public double StrokeStyleLineWidth { get; set; }
```

### Contoh

Kode berikut menunjukkan dukungan sumber daya VstkResource.

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

### Lihat juga

* class [VstkResource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* perakitan [Aspose.PSD](../../../)


