---
title: ImageCreatorsRegistry
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 4420
url: /net/aspose.psd/imagecreatorsregistry/
---
## ImageCreatorsRegistry class

Represents the image creators registry.

```csharp
public static class ImageCreatorsRegistry
```

## Properties

| Name | Description |
| --- | --- |
| static [RegisteredDescriptors](registereddescriptors) { get; } | Gets the registered descriptors. |
| static [RegisteredFormats](registeredformats) { get; } | Gets the registered image creation formats. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateFirstSupportedCreator](createfirstsupportedcreator)(ImageOptionsBase) | Creates the first found creator suitable for the specified. |
| static [GetFirstSupportedDescriptor](getfirstsupporteddescriptor)(ImageOptionsBase) | Gets the fist found supported descriptor suitable for the specified. |
| static [Register](register)(IImageCreatorDescriptor) | Registers the specified image creator descriptor. |
| static [RegisterCreator](registercreator)(IImageCreatorDescriptor) | Registers the creator. |
| static [UnregisterCreator](unregistercreator)(IImageCreatorDescriptor) | Unregisters the creator. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->