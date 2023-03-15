---
title: VogkResource.Length
second_title: Aspose.PSD per riferimento API .NET
description: VogkResource proprietà. Ottiene la lunghezza della risorsa del livello in byte.
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/length/
---
## VogkResource.Length property

Ottiene la lunghezza della risorsa del livello in byte.

```csharp
public override int Length { get; }
```

### Esempi

L'esempio seguente dimostra il supporto della risorsa VogkResource.

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

    // Lettura
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // La modifica
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Guarda anche

* class [VogkResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vogkresource/)
* assemblea [Aspose.PSD](../../../)


