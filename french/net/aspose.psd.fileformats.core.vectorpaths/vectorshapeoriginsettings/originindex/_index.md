---
title: VectorShapeOriginSettings.OriginIndex
second_title: Référence de l'API Aspose.PSD pour .NET
description: VectorShapeOriginSettings propriété. Obtient ou définit lindex de forme dorigine.
type: docs
weight: 120
url: /fr/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/
---
## VectorShapeOriginSettings.OriginIndex property

Obtient ou définit l'index de forme d'origine.

```csharp
public int OriginIndex { get; set; }
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

* class [VectorShapeOriginSettings](../)
* espace de noms [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* Assemblée [Aspose.PSD](../../../)


