---
title: BackgroundColorResource.DataSize
second_title: Aspose.PSD for .NET API Reference
description: BackgroundColorResource property. Gets the resource data size in bytes
type: docs
weight: 30
url: /net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
{{< psd/tize >}}
## BackgroundColorResource.DataSize property

Gets the resource data size in bytes.

```csharp
public override int DataSize { get; }
```

### Property Value

The resource data size.

## Examples

The following example demonstrates the support of BackgroundColorResource resource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // update BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### See Also

* class [BackgroundColorResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


