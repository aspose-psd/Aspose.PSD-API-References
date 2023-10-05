---
title: Interface IVectorPathData
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData interface. The interface for access to the vector path data
type: docs
weight: 1360
url: /net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
{{< psd/tize >}}
## IVectorPathData interface

The interface for access to the vector path data.

```csharp
public interface IVectorPathData
```

## Properties

| Name | Description |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | Gets or sets a value indicating whether this instance is disabled. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | Gets or sets a value indicating whether this instance is inverted. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | Gets or sets a value indicating whether this instance is not linked. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | Gets or sets the path records. |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | Gets or sets the version. |

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

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


