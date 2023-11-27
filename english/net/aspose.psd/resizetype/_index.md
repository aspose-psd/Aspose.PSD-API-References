---
title: Enum ResizeType
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.ResizeType enum. Specifies the resize type
type: docs
weight: 5610
url: /net/aspose.psd/resizetype/
---
{{< psd/tize >}}
## ResizeType enumeration

Specifies the resize type.

```csharp
public enum ResizeType
```

### Values

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

## Examples

The following code demonstrates how to resize an image with a new SinC resize type.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Load an existing image into an instance of PsdImage class
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

The following code demonstrates how to resize an image with a new Bell resize type.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Load an existing image into an instance of PsdImage class
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

The following code demonstrates how to resize an image with a new Mitchell resize type.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Load an existing image into an instance of PsdImage class
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

The following code demonstrates how to resize an image with a new CatmullRom resize type.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Load an existing image into an instance of PsdImage class
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

The following code demonstrates how to resize an image with a new CubicBSpline resize type.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Load an existing image into an instance of PsdImage class
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

The following code demonstrates how to resize an image with a new CubicConvolution resize type.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Load an existing image into an instance of PsdImage class
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


