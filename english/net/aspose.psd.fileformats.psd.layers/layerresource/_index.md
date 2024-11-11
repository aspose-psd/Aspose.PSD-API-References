---
title: Class LayerResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResource class. Represents layer info
type: docs
weight: 2430
url: /net/aspose.psd.fileformats.psd.layers/layerresource/
---
{{< psd/tize >}}
## LayerResource class

Represents layer info.

```csharp
public abstract class LayerResource
```

## Properties

| Name | Description |
| --- | --- |
| virtual [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Gets the layer resource key. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Gets the layer resource length in bytes. |
| abstract [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Gets the signature. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Save](../../aspose.psd.fileformats.psd.layers/layerresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [PsbResourceSignature](../../aspose.psd.fileformats.psd.layers/layerresource/psbresourcesignature/) | The PSB-specific resource signature. |
| const [ResourceSignature](../../aspose.psd.fileformats.psd.layers/layerresource/resourcesignature/) | The common resource signature. |

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


