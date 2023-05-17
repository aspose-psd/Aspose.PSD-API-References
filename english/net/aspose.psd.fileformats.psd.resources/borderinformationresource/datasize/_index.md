---
title: BorderInformationResource.DataSize
second_title: Aspose.PSD for .NET API Reference
description: BorderInformationResource property. Gets the resource data size in bytes
type: docs
weight: 20
url: /net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
{{< psd/tize >}}
## BorderInformationResource.DataSize property

Gets the resource data size in bytes.

```csharp
public override int DataSize { get; }
```

### Property Value

The resource data size.

## Examples

The following example demonstrates the support of BorderInformationResource resource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // update BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### See Also

* class [BorderInformationResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* assembly [Aspose.PSD](../../../)


