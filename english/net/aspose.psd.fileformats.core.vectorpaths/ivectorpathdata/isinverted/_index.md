---
title: IVectorPathData.IsInverted
second_title: Aspose.PSD for .NET API Reference
description: IVectorPathData property. Gets or sets a value indicating whether this instance is inverted
type: docs
weight: 20
url: /net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/
---
{{< psd/tize >}}
## IVectorPathData.IsInverted property

Gets or sets a value indicating whether this instance is inverted.

```csharp
public bool IsInverted { get; set; }
```

### Property Value

`true` if this instance is inverted; otherwise, `false`.

## Examples

This example demonstrates the support of 'WorkingPathResource' resource in PsdImage.ImageResources fo correct working of Crop operation.

```csharp
[C#]

// Crop image and save.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Search WorkingPathResource resource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 2572506 || record.Points[0].Y != 8535408)
    {
        throw new Exception("Values is incorrect.");
    }

    // Crop and save.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Load saved image and check the changes.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Search WorkingPathResource resource.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 4630510 || record.Points[0].Y != 22761088)
    {
        throw new Exception("Values is incorrect.");
    }
}
```

### See Also

* interface [IVectorPathData](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../ivectorpathdata/)
* assembly [Aspose.PSD](../../../)


