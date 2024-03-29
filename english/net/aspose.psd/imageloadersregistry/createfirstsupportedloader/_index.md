---
title: ImageLoadersRegistry.CreateFirstSupportedLoader
second_title: Aspose.PSD for .NET API Reference
description: ImageLoadersRegistry method. Creates the first found loader suitable for the specified stream and optionally the loadOptions
type: docs
weight: 30
url: /net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Creates the first found loader suitable for the specified *stream* and optionally the *loadOptions*.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |
| loadOptions | LoadOptions | The load options. |

### Return Value

The loader which supports the specified *stream* and *loadOptions* or null if no such loader is found.

## Remarks

The first loader will be actually the last registered.

### See Also

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


