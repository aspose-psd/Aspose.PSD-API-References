---
title: OSTypeStructuresRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD for .NET API Reference
description: OSTypeStructuresRegistry method. Gets the first supported opener descriptor
type: docs
weight: 20
url: /net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry.GetFirstSupportedDescriptor method

Gets the first supported opener descriptor.

```csharp
public static IOSTypeStructureLoader GetFirstSupportedDescriptor(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |

### Return Value

The layer resource loader descriptor or null if no loader descriptor supported for such stream.

## Remarks

The first loader will be actually the last registered.

### See Also

* interface [IOSTypeStructureLoader](../../iostypestructureloader/)
* class [OSTypeStructuresRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


