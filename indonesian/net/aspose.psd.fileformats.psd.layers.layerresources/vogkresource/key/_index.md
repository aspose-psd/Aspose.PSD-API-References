---
title: VogkResource.Key
second_title: Aspose.PSD untuk Referensi .NET API
description: VogkResource Properti. Mendapat kunci sumber daya lapisan.
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/key/
---
## VogkResource.Key property

Mendapat kunci sumber daya lapisan.

```csharp
public override int Key { get; }
```

### Contoh

Contoh berikut menunjukkan dukungan sumber daya VogkResource.

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // Membaca
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Mengedit
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Lihat juga

* class [VogkResource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vogkresource/)
* perakitan [Aspose.PSD](../../../)


