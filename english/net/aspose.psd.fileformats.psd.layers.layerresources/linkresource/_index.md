---
title: Class LinkResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource class. Defines the LinkResource class that contains information about linked or embedded files in the PSD format image. The link resource may contain several LinkDataSource instances which can be accessed by indexers in any derived class
type: docs
weight: 2950
url: /net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
{{< psd/tize >}}
## LinkResource class

Defines the LinkResource class that contains information about linked or embedded files in the PSD format image. The link resource may contain several [`LinkDataSource`](../linkdatasource/) instances which can be accessed by indexers in any derived class.

```csharp
public abstract class LinkResource : LayerResource
```

## Properties

| Name | Description |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Gets the count of link data sources which can be accessed by the indexer. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Gets a value indicating whether this link resource instance is empty. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Gets the [`LinkDataSource`](../linkdatasource/) at the specified index which is the link data source unique identifier.. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Gets the layer resource key. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Gets the PSD global link resource length in bytes. |
| [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Gets the signature. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Saves the resource block data. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

### See Also

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


