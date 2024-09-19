---
title: Class GridAndGuidesResouce
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Resources.GridAndGuidesResouce class. Represents the grid and guides resource
type: docs
weight: 4080
url: /net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---
{{< psd/tize >}}
## GridAndGuidesResouce class

Represents the grid and guides resource.

```csharp
public sealed class GridAndGuidesResouce : ResourceBlock
```

## Constructors

| Name | Description |
| --- | --- |
| [GridAndGuidesResouce](gridandguidesresouce/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/datasize/) { get; } | Gets the resource data size in bytes. |
| [GridCycleX](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcyclex/) { get; set; } | Gets or sets the horizontal grid cycle. The default is 576. |
| [GridCycleY](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcycley/) { get; set; } | Gets or sets the vertical grid cycle. The default is 576. |
| [GuideCount](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guidecount/) { get; } | Gets the guide resource blocks count. |
| [Guides](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guides/) { get; set; } | Gets or sets the guides. |
| [HeaderVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/headerversion/) { get; set; } | Gets or sets the header version. This value should be always 1. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Gets or sets the unique identifier for the resource. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/minimalversion/) { get; } | Gets the minimal required psd version. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Gets or sets the resource name. Pascal string, padded to make the size even (a null name consists of two bytes of 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Gets the resource signature. Should be always '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Gets the resource block size in bytes including its data. |

## Methods

| Name | Description |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Saves the resource block to the specified stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validates the resource values. |

### See Also

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


