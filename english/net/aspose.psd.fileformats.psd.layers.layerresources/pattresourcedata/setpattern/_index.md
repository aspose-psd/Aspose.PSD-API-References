---
title: PattResourceData.SetPattern
second_title: Aspose.PSD for .NET API Reference
description: PattResourceData method. Sets the pattern pixel buffer and target size updates Width / Height and stores the data for saving using the default compression mode 0
type: docs
weight: 110
url: /net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/setpattern/
---
{{< psd/tize >}}
## PattResourceData.SetPattern method

Sets the pattern pixel buffer and target size, updates [`Width`](../width/) / [`Height`](../height/), and stores the data for saving using the default compression mode (0).

```csharp
public void SetPattern(int[] pixels, Rectangle bounds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixels | Int32[] | 32-bit pixels in `0xAARRGGBB` format. |
| bounds | Rectangle | Pixel bounds of the pattern. |

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Pixels array length must be equal to bounds area. |

### See Also

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [PattResourceData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


