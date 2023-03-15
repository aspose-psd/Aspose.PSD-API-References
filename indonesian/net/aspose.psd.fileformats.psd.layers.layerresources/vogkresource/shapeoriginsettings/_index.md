---
title: VogkResource.ShapeOriginSettings
second_title: Aspose.PSD untuk Referensi .NET API
description: VogkResource Properti. Mendapat atau menyetel pengaturan asal bentuk.
type: docs
weight: 50
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/shapeoriginsettings/
---
## VogkResource.ShapeOriginSettings property

Mendapat atau menyetel pengaturan asal bentuk.

```csharp
public VectorShapeOriginSettings[] ShapeOriginSettings { get; set; }
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

* class [VectorShapeOriginSettings](../../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/)
* class [VogkResource](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vogkresource/)
* perakitan [Aspose.PSD](../../../)


