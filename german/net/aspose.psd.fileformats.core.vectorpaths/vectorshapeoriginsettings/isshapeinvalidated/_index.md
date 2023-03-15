---
title: VectorShapeOriginSettings.IsShapeInvalidated
second_title: Aspose.PSD für .NET-API-Referenz
description: VectorShapeOriginSettings eigendom. Ruft einen Wert ab oder legt einen Wert fest der angibt ob die Form ungültig ist.
type: docs
weight: 80
url: /de/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/
---
## VectorShapeOriginSettings.IsShapeInvalidated property

Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Form ungültig ist.

```csharp
public bool IsShapeInvalidated { get; set; }
```

### Beispiele

Das folgende Beispiel demonstriert die Unterstützung der VogkResource-Ressource.

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

    // Lektüre
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Bearbeiten
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Siehe auch

* class [VectorShapeOriginSettings](../)
* namensraum [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* Montage [Aspose.PSD](../../../)


