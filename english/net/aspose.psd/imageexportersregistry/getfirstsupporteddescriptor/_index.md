---
title: ImageExportersRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD for .NET API Reference
description: ImageExportersRegistry method. Gets the fist found supported descriptor suitable for the specified save options and image
type: docs
weight: 40
url: /net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Gets the fist found supported descriptor suitable for the specified save options and image.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Image | The image to export. |
| options | ImageOptionsBase | The options. |

### Return Value

The exporter descriptor which supports the specified image and save options or null if no such descriptor is found.

## Remarks

The first exporter descriptor will be actually the last registered.

### See Also

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


