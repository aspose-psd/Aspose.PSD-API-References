---
title: VectorShapeOriginSettings.IsShapeInvalidated
second_title: Aspose.PSD για Αναφορά API .NET
description: VectorShapeOriginSettings ιδιοκτησία. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το σχήμα είναι άκυρο.
type: docs
weight: 80
url: /el/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isshapeinvalidated/
---
## VectorShapeOriginSettings.IsShapeInvalidated property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το σχήμα είναι άκυρο.

```csharp
public bool IsShapeInvalidated { get; set; }
```

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει την υποστήριξη του πόρου VogkResource.

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

    // ΑΝΑΓΝΩΣΗ
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Επεξεργασία
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Δείτε επίσης

* class [VectorShapeOriginSettings](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* συνέλευση [Aspose.PSD](../../../)


