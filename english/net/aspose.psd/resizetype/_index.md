---
title: ResizeType
second_title: Aspose.PSD for .NET API Reference
description: 
type: docs
weight: 5170
url: /net/aspose.psd/resizetype/
---
## ResizeType enumeration

Specifies the resize type.

```csharp
public enum ResizeType
```

## Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | The pixels are not preserved during resize operation. |
| LeftTopToLeftTop | `1` | Left top point of the new image will coincide with the left top point of the original image. Crop will occur if required. |
| RightTopToRightTop | `2` | Right top point of the new image will coincide with the right top point of the original image. Crop will occur if required. |
| RightBottomToRightBottom | `3` | Right bottom point of the new image will coincide with the right bottom point of the original image. Crop will occur if required. |
| LeftBottomToLeftBottom | `4` | Left bottom point of the new image will coincide with the left bottom point of the original image. Crop will occur if required. |
| CenterToCenter | `5` | Center of the new image will coincide with the center of the original image. Crop will occur if required. |
| LanczosResample | `6` | Resample using lanczos algorithm with a=3. |
| NearestNeighbourResample | `7` | Resample using nearest neighbour algorithm. |
| AdaptiveResample | `8` | Resample using adaptive algorithm based on weighted and blended rational function and lanczos3 interpolation algorithms. |
| BilinearResample | `9` | Resample using bilinear interpolation. Image pre-filtering is allowed to remove the noice before resample, when needed |
| HighQualityResample | `10` | The high quality resample |
| CatmullRom | `11` | The Catmull-Rom cubic interpolation method. |
| CubicConvolution | `12` | The Cubic Convolution interpolation method |
| CubicBSpline | `13` | The CubicBSpline cubic interpolation method |
| Mitchell | `14` | The Mitchell cubic interpolation method |
| SinC | `15` | The Sinc (Lanczos3) cubic interpolation method |
| Bell | `16` | The Bell interpolation method |

### See Also

* namespace [Aspose.PSD](../../aspose.psd)
* assembly [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->