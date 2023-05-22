---
title: Class PrintFlagsResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Resources.PrintFlagsResource class. Print flags resource
type: docs
weight: 3950
url: /net/aspose.psd.fileformats.psd.resources/printflagsresource/
---
{{< psd/tize >}}
## PrintFlagsResource class

Print flags resource

```csharp
public sealed class PrintFlagsResource : ResourceBlock
```

## Constructors

| Name | Description |
| --- | --- |
| [PrintFlagsResource](printflagsresource/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BleedScale](../../aspose.psd.fileformats.psd.resources/printflagsresource/bleedscale/) { get; set; } | Gets or sets the bleed scale. |
| [BleedWidth](../../aspose.psd.fileformats.psd.resources/printflagsresource/bleedwidth/) { get; set; } | Gets or sets the width of the bleed. |
| [CenterCropMark](../../aspose.psd.fileformats.psd.resources/printflagsresource/centercropmark/) { get; set; } | Gets or sets the center crop mark. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/printflagsresource/datasize/) { get; } | Gets the resource data size in bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Gets or sets the unique identifier for the resource. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/printflagsresource/minimalversion/) { get; } | Gets the minimal required PSD version. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Gets the resource signature. Should be always '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Gets the resource block size in bytes including its data. |
| [Version](../../aspose.psd.fileformats.psd.resources/printflagsresource/version/) { get; set; } | Gets or sets the version. |

## Methods

| Name | Description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Saves the resource block to the specified stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validates the resource values. |

### See Also

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


