---
title: PsdImage.HorizontalResolution
second_title: Aspose.PSD for .NET API Reference
description: PsdImage property. Gets or sets the horizontal resolution in pixels per inch of this PsdImage
type: docs
weight: 170
url: /net/aspose.psd.fileformats.psd/psdimage/horizontalresolution/
---
{{< psd/tize >}}
## PsdImage.HorizontalResolution property

Gets or sets the horizontal resolution, in pixels per inch, of this [`PsdImage`](../).

```csharp
public override double HorizontalResolution { get; set; }
```

### Property Value

The horizontal resolution.

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | ResolutionInfo resource not found and can not set proper resolution |

## Remarks

Default value for PSD is 72, so if [`ResolutionInfoResource`](../../../aspose.psd.fileformats.psd.resources/resolutioninforesource/) wasn't found, this value is returned.

### See Also

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


