---
title: Class BorderInformationResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Resources.BorderInformationResource class. The resource with border information of image print settings
type: docs
weight: 4070
url: /net/aspose.psd.fileformats.psd.resources/borderinformationresource/
---
{{< psd/tize >}}
## BorderInformationResource class

The resource with border information of image print settings.

```csharp
public sealed class BorderInformationResource : ResourceBlock
```

## Constructors

| Name | Description |
| --- | --- |
| [BorderInformationResource](borderinformationresource/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/) { get; } | Gets the resource data size in bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Gets or sets the unique identifier for the resource. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/) { get; } | Gets the minimal required PSD version. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Gets the resource signature. Should be always '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Gets the resource block size in bytes including its data. |
| [Unit](../../aspose.psd.fileformats.psd.resources/borderinformationresource/unit/) { get; set; } | Gets or sets the border units. |
| [Width](../../aspose.psd.fileformats.psd.resources/borderinformationresource/width/) { get; set; } | Gets or sets the border width. |

## Methods

| Name | Description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Saves the resource block to the specified stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validates the resource values. |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


