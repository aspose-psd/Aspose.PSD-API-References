---
title: Class ImageExportersRegistry
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.ImageExportersRegistry class. Represents the image exporters registry
type: docs
weight: 5030
url: /net/aspose.psd/imageexportersregistry/
---
{{< psd/tize >}}
## ImageExportersRegistry class

Represents the image exporters registry.

```csharp
public static class ImageExportersRegistry
```

## Properties

| Name | Description |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.psd/imageexportersregistry/registeredexporterdescriptors/) { get; } | Gets the registered exporter descriptors. |
| static [RegisteredFormats](../../aspose.psd/imageexportersregistry/registeredformats/) { get; } | Gets the registered export formats. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.psd/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | Creates the first found exporter suitable for the specified save options and image. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | Gets the fist found supported descriptor suitable for the specified save options and image. |
| static [Register](../../aspose.psd/imageexportersregistry/register/)(IImageExporterDescriptor) | Registers the specified image exporter descriptor. |
| static [RegisterExporter](../../aspose.psd/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | Registers the exporter. |
| static [UnregisterExporter](../../aspose.psd/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | Unregisters the exporter. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


