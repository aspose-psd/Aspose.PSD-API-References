---
title: ImageExtensions.ToGdiImage
second_title: Aspose.PSD for .NET API Reference
description: ImageExtensions method. Converts the Image to the Image
type: docs
weight: 10
url: /net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Converts the [`Image`](../../../aspose.psd/image/) to the Image.

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | Image | The [`Image`](../../../aspose.psd/image/) to convert. |

### Return Value

The converted Image.

## Remarks

Warning, the GDI image may get lower bounds than *image* has. To get all parts of the image use more safe extension method ToGdiImageFull.

### See Also

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../imageextensions/)
* assembly [Aspose.PSD](../../../)


