---
title: VogkResource.ShapeOriginSettings
second_title: Aspose.PSD per riferimento API .NET
description: VogkResource proprietà. Ottiene o imposta le impostazioni dellorigine della forma.
type: docs
weight: 50
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/shapeoriginsettings/
---
## VogkResource.ShapeOriginSettings property

Ottiene o imposta le impostazioni dell'origine della forma.

```csharp
public VectorShapeOriginSettings[] ShapeOriginSettings { get; set; }
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

* class [VectorShapeOriginSettings](../../../aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/)
* class [VogkResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vogkresource/)
* assemblea [Aspose.PSD](../../../)


