---
title: VogkResource.PsdVersion
second_title: Référence de l'API Aspose.PSD pour .NET
description: VogkResource propriété. Obtient la version minimale de psd requise pour la ressource de couche. 0 indique aucune restriction.
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/psdversion/
---
## VogkResource.PsdVersion property

Obtient la version minimale de psd requise pour la ressource de couche. 0 indique aucune restriction.

```csharp
public override int PsdVersion { get; }
```

### Exemples

L'exemple suivant illustre la prise en charge de la ressource VogkResource.

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

    // En lisant
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Édition
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Voir également

* class [VogkResource](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vogkresource/)
* Assemblée [Aspose.PSD](../../../)


