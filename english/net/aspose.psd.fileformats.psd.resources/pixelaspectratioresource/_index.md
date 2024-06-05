---
title: Class PixelAspectRatioResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Resources.PixelAspectRatioResource class. Pixel aspect ration resource
type: docs
weight: 4090
url: /net/aspose.psd.fileformats.psd.resources/pixelaspectratioresource/
---
{{< psd/tize >}}
## PixelAspectRatioResource class

Pixel aspect ration resource

```csharp
public sealed class PixelAspectRatioResource : ResourceBlock
```

## Constructors

| Name | Description |
| --- | --- |
| [PixelAspectRatioResource](pixelaspectratioresource/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AspectRatio](../../aspose.psd.fileformats.psd.resources/pixelaspectratioresource/aspectratio/) { get; set; } | Gets or sets the aspect ratio. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/pixelaspectratioresource/datasize/) { get; } | Gets the resource data size in bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Gets or sets the unique identifier for the resource. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/pixelaspectratioresource/minimalversion/) { get; } | Gets the minimal required PSD version. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Gets the resource signature. Should be always '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Gets the resource block size in bytes including its data. |
| [Version](../../aspose.psd.fileformats.psd.resources/pixelaspectratioresource/version/) { get; set; } | Gets or sets the version. |

## Methods

| Name | Description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Saves the resource block to the specified stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validates the resource values. |

### See Also

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


