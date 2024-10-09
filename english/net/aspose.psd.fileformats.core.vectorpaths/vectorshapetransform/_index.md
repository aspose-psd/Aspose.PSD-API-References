---
title: Class VectorShapeTransform
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Core.VectorPaths.VectorShapeTransform class. Defines vector shape transformation matrix class
type: docs
weight: 1470
url: /net/aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/
---
{{< psd/tize >}}
## VectorShapeTransform class

Defines vector shape transformation matrix class

```csharp
public sealed class VectorShapeTransform
```

## Constructors

| Name | Description |
| --- | --- |
| [VectorShapeTransform](vectorshapetransform/)() | Initializes a new instance of the `VectorShapeTransform` class. |

## Properties

| Name | Description |
| --- | --- |
| [Tx](../../aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/tx/) { get; set; } | Gets or sets the TX value. |
| [Ty](../../aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/ty/) { get; set; } | Gets or sets the TY value. |
| [Xx](../../aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/xx/) { get; set; } | Gets or sets the XX value. |
| [Xy](../../aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/xy/) { get; set; } | Gets or sets the XY value. |
| [Yx](../../aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/yx/) { get; set; } | Gets or sets the YX value. |
| [Yy](../../aspose.psd.fileformats.core.vectorpaths/vectorshapetransform/yy/) { get; set; } | Gets or sets the YY value. |

## Examples

The following code demonstrate the ability to resize a shape layers that contains vector paths.

```csharp
[C#]

string sourceFileName = "vectorShapes.psd";
string outputFileName = "out_vectorShapes.psd";
string sourcePath = sourceFileName;
string outputPath = outputFileName;
string outputPathPng = Path.ChangeExtension(outputPath, ".png");
using (var psdImage = (PsdImage)Image.Load(sourcePath))
{
    foreach (var layer in psdImage.Layers)
    {
        layer.Resize(layer.Width * 5 / 4, layer.Height / 2);
    }

    psdImage.Save(outputPath);
    psdImage.Save(outputPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

This example shows how to get and set new Transform and OriginBoxCorners properties of ShapeOriginSettings in the Vogk resource of FillLayer in the PSD file.

```csharp
[C#]

// This example shows how to get and set new Transform and OriginBoxCorners properties
// of ShapeOriginSettings in the Vogk resource of FillLayer in the PSD file
string sourceFileName = "vectorShape_25_50.psd";
string outputPath = "result.psd";

VectorShapeOriginSettings originalSetting;
const int layerIndex = 0;

// Load the original image
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    AssertIsTrue(layerIndex < image.Layers.Length);
    var layer = image.Layers[layerIndex];
    AssertIsTrue(layer is ShapeLayer);
    var resource = GetVogkResource(layer);
    AssertAreEqual(1, resource.ShapeOriginSettings.Length);

    // Assert after reading
    var setting = resource.ShapeOriginSettings[0];
    AssertAreEqual(false, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(false, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(0, setting.OriginIndex);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(5, setting.OriginType);
    AssertAreEqual(true, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(Rectangle.FromLeftTopRightBottom(3, 7, 10, 22), setting.OriginShapeBox.Bounds);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(300d, setting.OriginResolution);

    // Assert new properties
    AssertAreEqual(true, setting.IsTransformPresent);
    AssertAreEqual(0d, setting.Transform.Tx);
    AssertAreEqual(0d, setting.Transform.Ty);
    AssertAreEqual(0.050000000000000003d, setting.Transform.Xx);
    AssertAreEqual(0d, setting.Transform.Yx);
    AssertAreEqual(0d, setting.Transform.Xy);
    AssertAreEqual(0.1d, setting.Transform.Yy);
    AssertAreEqual(true, setting.IsOriginBoxCornersPresent);
    AssertAreEqual(2.9000000000000004d, setting.OriginBoxCorners[0]);
    AssertAreEqual(7.3000000000000007d, setting.OriginBoxCorners[1]);
    AssertAreEqual(10.450000000000001d, setting.OriginBoxCorners[2]);
    AssertAreEqual(7.3000000000000007d, setting.OriginBoxCorners[3]);
    AssertAreEqual(10.450000000000001d, setting.OriginBoxCorners[4]);
    AssertAreEqual(22.400000000000002d, setting.OriginBoxCorners[5]);
    AssertAreEqual(2.9000000000000004d, setting.OriginBoxCorners[6]);
    AssertAreEqual(22.400000000000002d, setting.OriginBoxCorners[7]);

    // Set new properties
    originalSetting = resource.ShapeOriginSettings[0];
    originalSetting.Transform.Tx = 0.2d;
    originalSetting.Transform.Ty = 0.3d;
    originalSetting.Transform.Xx = 0.4d;
    originalSetting.Transform.Xy = 0.5d;
    originalSetting.Transform.Yx = 0.6d;
    originalSetting.Transform.Yy = 0.7d;
    originalSetting.OriginBoxCorners = new double[8] { 9, 8, 7, 6, 5, 4, 3, 2 };

    // Save this PSD image with changed propeties.
    image.Save(outputPath, new PsdOptions(image));
}

// Load the saved PSD image with changed propeties.
using (PsdImage image = (PsdImage)Image.Load(outputPath))
{
    var layer = image.Layers[layerIndex];
    AssertIsTrue(layer is ShapeLayer);
    var resource = GetVogkResource(layer);
    AssertAreEqual(1, resource.ShapeOriginSettings.Length);

    // Assert that properties are saved and loaded correctly 
    var setting = resource.ShapeOriginSettings[0];
    AssertAreEqual(true, setting.IsOriginIndexPresent);
    AssertAreEqual(false, setting.IsShapeInvalidatedPresent);
    AssertAreEqual(true, setting.IsOriginResolutionPresent);
    AssertAreEqual(true, setting.IsOriginTypePresent);
    AssertAreEqual(true, setting.IsOriginShapeBBoxPresent);
    AssertAreEqual(false, setting.IsOriginRadiiRectanglePresent);
    AssertAreEqual(0, setting.OriginIndex);
    AssertAreEqual(true, setting.IsTransformPresent);
    AssertAreEqual(0.2d, setting.Transform.Tx);
    AssertAreEqual(0.3d, setting.Transform.Ty);
    AssertAreEqual(0.4d, setting.Transform.Xx);
    AssertAreEqual(0.5d, setting.Transform.Xy);
    AssertAreEqual(0.6d, setting.Transform.Yx);
    AssertAreEqual(0.7d, setting.Transform.Yy);
    AssertAreEqual(true, setting.IsOriginBoxCornersPresent);
    AssertAreEqual(originalSetting.OriginBoxCorners[0], setting.OriginBoxCorners[0]);
    AssertAreEqual(originalSetting.OriginBoxCorners[1], setting.OriginBoxCorners[1]);
    AssertAreEqual(originalSetting.OriginBoxCorners[2], setting.OriginBoxCorners[2]);
    AssertAreEqual(originalSetting.OriginBoxCorners[3], setting.OriginBoxCorners[3]);
    AssertAreEqual(originalSetting.OriginBoxCorners[4], setting.OriginBoxCorners[4]);
    AssertAreEqual(originalSetting.OriginBoxCorners[5], setting.OriginBoxCorners[5]);
    AssertAreEqual(originalSetting.OriginBoxCorners[6], setting.OriginBoxCorners[6]);
    AssertAreEqual(originalSetting.OriginBoxCorners[7], setting.OriginBoxCorners[7]);
}

VogkResource GetVogkResource(Layer layer)
{
    if (layer == null)
    {
        throw new PsdImageArgumentException("The parameter layer should not be null.");
    }

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new PsdImageException("VogkResource not found.");
    }

    return resource;
}

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}
```

### See Also

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


