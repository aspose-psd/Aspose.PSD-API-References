---
title: VectorShapeOriginSettings.OriginIndex
second_title: Aspose.PSD för .NET API-referens
description: VectorShapeOriginSettings fast egendom. Hämtar eller ställer in ursprungsformindex.
type: docs
weight: 120
url: /sv/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/
---
## VectorShapeOriginSettings.OriginIndex property

Hämtar eller ställer in ursprungsformindex.

```csharp
public int OriginIndex { get; set; }
```

### Exempel

Följande exempel visar stödet för VogkResource-resursen.

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

    // Läser
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // Redigering
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### Se även

* class [VectorShapeOriginSettings](../)
* namnutrymme [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* hopsättning [Aspose.PSD](../../../)


