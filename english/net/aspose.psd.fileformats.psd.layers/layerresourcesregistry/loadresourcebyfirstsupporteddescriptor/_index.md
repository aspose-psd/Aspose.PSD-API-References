---
title: LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor
second_title: Aspose.PSD for .NET API Reference
description: LayerResourcesRegistry method. Loads LayerResource using first found opener suitable for the specified stream
type: docs
weight: 40
url: /net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

Loads [`LayerResource`](../../layerresource/) using first found opener suitable for the specified *stream*.

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |
| psdVersion | Int32 | The PSD version. |

### Return Value

The loaded [`LayerResource`](../../layerresource/) or null if no opener is found.

## Remarks

The first opener will be actually the last registered.

### See Also

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


