---
title: Enum InterpolationMode
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.InterpolationMode enum. The InterpolationMode enumeration specifies the algorithm that is used when images are scaled or rotated
type: docs
weight: 5090
url: /net/aspose.psd/interpolationmode/
---
{{< psd/tize >}}
## InterpolationMode enumeration

The `InterpolationMode` enumeration specifies the algorithm that is used when images are scaled or rotated.

```csharp
public enum InterpolationMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Invalid | `-1` | Invalid interpolation mode. |
| Default | `0` | Specifies default mode. |
| Low | `1` | Specifies low quality interpolation. |
| High | `2` | Specifies high quality interpolation. |
| Bilinear | `3` | Specifies bilinear interpolation. No prefiltering is done. This mode is not suitable for shrinking an image below 50 percent of its original size. |
| Bicubic | `4` | Specifies bicubic interpolation. No prefiltering is done. This mode is not suitable for shrinking an image below 25 percent of its original size. |
| NearestNeighbor | `5` | Specifies nearest-neighbor interpolation. |
| HighQualityBilinear | `6` | Specifies high-quality, bilinear interpolation. Prefiltering is performed to ensure high-quality shrinking. |
| HighQualityBicubic | `7` | Specifies high-quality, bicubic interpolation. Prefiltering is performed to ensure high-quality shrinking. This mode produces the highest quality transformed images. |

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


