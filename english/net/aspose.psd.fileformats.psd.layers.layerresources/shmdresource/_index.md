---
title: Class ShmdResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ShmdResource class. Class ShmdResource. Metadata settings
type: docs
weight: 3300
url: /net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/
---
{{< psd/tize >}}
## ShmdResource class

Class ShmdResource. Metadata settings

```csharp
public class ShmdResource : LayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [ShmdResource](shmdresource/#constructor)() | Initializes a new instance of the `ShmdResource` class. |
| [ShmdResource](shmdresource/#constructor_1)(byte[]) | Initializes a new instance of the `ShmdResource` class. |

## Properties

| Name | Description |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Gets the layer resource key. |
| [LayerCreatedDateTime](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/layercreateddatetime/) { get; set; } | Gets or sets the layer created time. If Layer created time not specified then returns new DateTime(0) |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/length/) { get; } | Gets the layer resource length in bytes. |
| [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Gets the signature. |
| [SubResources](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/) { get; } | Gets the sub resources of shmd resource. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/save/)(StreamContainer, int) | Saves the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [SubResourceHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresourceheaderlength/) | The sub resource header length |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/shmdresource/typetoolkey/) | The type tool info key. |

### See Also

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


