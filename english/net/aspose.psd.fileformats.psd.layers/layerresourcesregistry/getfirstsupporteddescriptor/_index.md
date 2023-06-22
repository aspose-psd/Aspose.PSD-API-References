---
title: LayerResourcesRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD for .NET API Reference
description: LayerResourcesRegistry method. Gets the first supported opener descriptor
type: docs
weight: 20
url: /net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

Gets the first supported opener descriptor.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |
| psdVersion | Int32 | The PSD version. |

### Return Value

The layer resource loader descriptor or null if no loader descriptor supported for such stream.

## Remarks

The first loader will be actually the last registered.

### See Also

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


