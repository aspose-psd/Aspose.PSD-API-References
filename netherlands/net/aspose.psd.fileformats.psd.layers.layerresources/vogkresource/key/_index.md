---
title: VogkResource.Key
second_title: Aspose.PSD voor .NET API-referentie
description: VogkResource eigendom. Haalt de laagbronsleutel op.
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/key/
---
## VogkResource.Key property

Haalt de laagbronsleutel op.

```csharp
public override int Key { get; }
```

### Voorbeelden

Het volgende voorbeeld demonstreert de ondersteuning van VogkResource-resource.

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

    // Lezing
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Bewerken
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Zie ook

* class [VogkResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vogkresource/)
* montage [Aspose.PSD](../../../)


