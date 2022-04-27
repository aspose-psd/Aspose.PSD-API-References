---
title: GetFirstSupportedDescriptorByTypeName
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 60
url: /net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptorByTypeName method

Gets the first supported descriptor by its type name.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByTypeName(
    string descriptorTypeName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| descriptorTypeName | String | The descriptor type name. |

## Return Value

The first found loader descriptor or null if not such descriptor is found.

### Remarks

The first loader descriptor will be actually the last registered.

### See Also

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor)
* class [ImageLoadersRegistry](../../imageloadersregistry)
* namespace [Aspose.PSD](../../imageloadersregistry)
* assembly [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->