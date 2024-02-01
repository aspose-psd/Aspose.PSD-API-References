---
title: BackgroundColorResource.MinimalVersion
second_title: Aspose.PSD for .NET API Reference
description: BackgroundColorResource property. Gets the minimal required PSD version
type: docs
weight: 40
url: /net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
{{< psd/tize >}}
## BackgroundColorResource.MinimalVersion property

Gets the minimal required PSD version.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

The minimal PSD version.

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


