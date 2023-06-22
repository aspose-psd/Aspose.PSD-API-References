---
title: GifOptions.ColorResolution
second_title: Aspose.PSD for .NET API Reference
description: GifOptions property. Gets or sets the GIF color resolution
type: docs
weight: 30
url: /net/aspose.psd.imageoptions/gifoptions/colorresolution/
---
{{< psd/tize >}}
## GifOptions.ColorResolution property

Gets or sets the GIF color resolution.

```csharp
public byte ColorResolution { get; set; }
```

### Property Value

The color resolution.

## Remarks

Color Resolution - Number of bits per primary color available to the original image, minus 1. This value represents the size of the entire palette from which the colors in the graphic were selected, not the number of colors actually used in the graphic. For example, if the value in this field is 3, then the palette of the original image had 4 bits per primary color available to create the image. This value should be set to indicate the richness of the original palette, even if not every color from the whole palette is available on the source machine.

### See Also

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


