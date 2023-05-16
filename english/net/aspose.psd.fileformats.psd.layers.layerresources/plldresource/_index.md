---
title: Class PlLdResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PlLdResource class. Defines the PlLdResource class that contains information about a placed layer in the PSD file. Is is used to support smart object layers in the Adobe Photoshop images. It was replaced by SoLdResource in the Adobe Photoshop CS3
type: docs
weight: 2960
url: /net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/
---
{{< psd/tize >}}
## PlLdResource class

Defines the PlLdResource class that contains information about a placed layer in the PSD file. Is is used to support smart object layers in the Adobe® Photoshop® images. It was replaced by SoLdResource in the Adobe® Photoshop® CS3

```csharp
public class PlLdResource : PlacedResource
```

## Properties

| Name | Description |
| --- | --- |
| virtual [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/antialiaspolicy/) { get; set; } | Gets or sets the anti alias policy of the placed layer in the PSD image. |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bottom/) { get; set; } | Gets or sets the bottom location of the placed layer in the PSD image. |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/bounds/) { get; set; } | Gets or sets the bounds of the placed layer in the PSD file. |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpoints/) { get; set; } | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/horizontalmeshpointunit/) { get; set; } | Gets or sets the measure unit of the horizontal mesh points. |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/iscustom/) { get; set; } | Gets or sets a value indicating whether this instance warp style is custom. If true it contains mesh points. If set to false it erases mesh points. |
| virtual [Items](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/items/) { get; set; } | Gets or sets the warp items. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/plldresource/key/) { get; } | Gets the PlLd resource key. |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/left/) { get; set; } | Gets or sets the left location of the placed layer in the PSD file. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/plldresource/length/) { get; } | Gets the PlLd resource length in bytes. |
| virtual [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/pagenumber/) { get; set; } | Gets or sets the page number of the placed layer in the PSD file. |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspective/) { get; set; } | Gets or sets the perspective value of the placed layer in the PSD file. |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/perspectiveother/) { get; set; } | Gets or sets the perspective other value of the placed layer in the PSD file. |
| virtual [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/placedlayertype/) { get; set; } | Gets or sets the type of the placed layer in the PSD file. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/plldresource/psdversion/) { get; } | Gets the minimal psd version required for the PlLd resource. 0 indicates no restrictions. |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/right/) { get; set; } | Gets or sets the right location of the placed layer in the PSD file. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/plldresource/signature/) { get; } | Gets the PlLd resource signature. |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/top/) { get; set; } | Gets or sets the top location of the placed layer in the PSD image. |
| virtual [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/totalpages/) { get; set; } | Gets or sets the total pages of the placed layer in the PSD file. |
| virtual [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/transformmatrix/) { get; set; } | Gets or sets the transform matrix of the placed layer in the PSD file. |
| virtual [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uniqueid/) { get; set; } | Gets or sets the global unique identifier of the placed layer in the PSD image. |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/uorder/) { get; set; } | Gets or sets the U order value of the placed layer in the PSD file. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/value/) { get; set; } | Gets or sets the warp value of the placed layer in the PSD image. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/version/) { get; } | Gets the version of the placed layer in the PSD file, usually 3. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpoints/) { get; set; } | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/verticalmeshpointunit/) { get; set; } | Gets or sets the measure unit of the vertical mesh points. |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/vorder/) { get; set; } | Gets or sets the V order value of the placed layer in the PSD file. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/plldresource/save/)(StreamContainer, int) | Saves the PlLD resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/plldresource/typetoolkey/) | The type tool info key. |

## Examples

The following code demonstrates the support of the PlLdResource resource.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    var areEqual = object.Equals(actual, expected);
    if (!areEqual && actual is Array && expected is Array)
    {
        var actualArray = (Array)actual;
        var expectedArray = (Array)actual;
        if (actualArray.Length == expectedArray.Length)
        {
            for (int i = 0; i < actualArray.Length; i++)
            {
                if (!object.Equals(actualArray.GetValue(i), expectedArray.GetValue(i)))
                {
                    break;
                }
            }

            areEqual = true;
        }
    }

    if (!areEqual)
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
var outputFilePath = "LayeredSmartObjects8bit2_output.psd";
var expectedValues = new object[]
{
    new object[]
    {
        true,
        "76f05a3b-7523-5e42-a1bb-27f4735bffa0",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            29.937922786050663,
            95.419959734187131,
            126.85445817782261,
            1.0540625423957124,
            172.20861031651307,
            47.634102808208553,
            75.292074924741144,
            142
        },
        0d,
        0d,
        0d,
        0d,
        0d,
        149d,
        310d,
        4,
        4,
        UnitTypes.Pixels,
        new double[16]
        {
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d,
            0.0d, 103.33333333333333d, 206.66666666666666d, 310.0d
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0d, 0.0d, 0.0d, 0.0d,
            49.666666666666664d, 49.666666666666664d, 49.666666666666664d, 49.666666666666664d,
            99.333333333333329d, 99.333333333333329d, 99.333333333333329d, 99.333333333333329d,
            149, 149, 149, 149,
        },
    },
    new object[]
    {
        true,
        "cf0477a8-8f92-ac4f-9462-f78e26234851",
        1,
        1,
        0x10,
        PlacedLayerType.Raster,
        new double[8]
        {
            37.900314592235681,
            -0.32118219433001371,
            185.94210608826535,
            57.7076819802063,
            153.32047433609358,
            140.9311755779743,
            5.2786828400639294,
            82.902311403437977,
        },
        0d,
        0d,
        0d,
        0d,
        0d,
        721d,
        1280d,
        4,
        4,
        UnitTypes.Pixels,
        new double[16]
        {
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
            0.0, 426.66666666666663, 853.33333333333326, 1280,
        },
        UnitTypes.Pixels,
        new double[16]
        {
            0.0, 0.0, 0.0, 0.0,
            240.33333333333331, 240.33333333333331, 240.33333333333331, 240.33333333333331,
            480.66666666666663, 480.66666666666663, 480.66666666666663, 480.66666666666663,
            721, 721, 721, 721,
        },
        0,
        0
    }
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    PlLdResource resource = null;
    int index = 0;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            resource = imageResource as PlLdResource;
            if (resource != null)
            {
                var expectedValue = (object[])expectedValues[index++];
                AssertAreEqual(expectedValue[0], resource.IsCustom);
                AssertAreEqual(expectedValue[1], resource.UniqueId.ToString());
                AssertAreEqual(expectedValue[2], resource.PageNumber);
                AssertAreEqual(expectedValue[3], resource.TotalPages);
                AssertAreEqual(expectedValue[4], resource.AntiAliasPolicy);
                AssertAreEqual(expectedValue[5], resource.PlacedLayerType);
                AssertAreEqual(8, resource.TransformMatrix.Length);
                AssertAreEqual((double[])expectedValue[6], resource.TransformMatrix);
                AssertAreEqual(expectedValue[7], resource.Value);
                AssertAreEqual(expectedValue[8], resource.Perspective);
                AssertAreEqual(expectedValue[9], resource.PerspectiveOther);
                AssertAreEqual(expectedValue[10], resource.Top);
                AssertAreEqual(expectedValue[11], resource.Left);
                AssertAreEqual(expectedValue[12], resource.Bottom);
                AssertAreEqual(expectedValue[13], resource.Right);
                AssertAreEqual(expectedValue[14], resource.UOrder);
                AssertAreEqual(expectedValue[15], resource.VOrder);
                if (resource.IsCustom)
                {
                    AssertAreEqual(expectedValue[16], resource.HorizontalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[17], resource.HorizontalMeshPoints);
                    AssertAreEqual(expectedValue[18], resource.VerticalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[19], resource.VerticalMeshPoints);
                    var temp = resource.VerticalMeshPoints;
                    resource.VerticalMeshPoints = resource.HorizontalMeshPoints;
                    resource.HorizontalMeshPoints = temp;
                }
                
                resource.PageNumber = 2;
                resource.TotalPages = 3;
                resource.AntiAliasPolicy = 30;
                resource.Value = 1.23456789;
                resource.Perspective = 0.123456789;
                resource.PerspectiveOther = 0.987654321;
                resource.Top = -126;
                resource.Left = -215;
                resource.Bottom = 248;
                resource.Right = 145;

                // Be careful with some parameters: image may became unreadable by Adobe® Photoshop®
                ////resource.UOrder = 6;
                ////resource.VOrder = 9;

                // Do no change this otherwise you won't be able to use free transform
                // or change the underlining smart object to the vector type
                ////resource.PlacedLayerType = PlacedLayerType.Vector;

                // There should be valid PlLdResource with this unique Id
                ////resource.UniqueId = new Guid("98765432-10fe-cba0-1234-56789abcdef0");

                break;
            }
        }
    }

    AssertAreEqual(true, resource != null);
    image.Save(outputFilePath, new PsdOptions(image));
}
```

### See Also

* class [PlacedResource](../placedresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


