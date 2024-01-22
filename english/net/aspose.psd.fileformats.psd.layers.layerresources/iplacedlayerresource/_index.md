---
title: Interface IPlacedLayerResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IPlacedLayerResource interface. Defines the IPlacedLayerResource interface that contains information about a placed layer in the PSD file. Is is a markup interface used to designate PlLd Sold and Sole resources in the Adobe Photoshop images. Is is used to support smart object layers in the Adobe Photoshop images
type: docs
weight: 2690
url: /net/aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/
---
{{< psd/tize >}}
## IPlacedLayerResource interface

Defines the IPlacedLayerResource interface that contains information about a placed layer in the PSD file. Is is a markup interface used to designate PlLd, Sold and Sole resources in the Adobe® Photoshop® images. Is is used to support smart object layers in the Adobe® Photoshop® images.

```csharp
public interface IPlacedLayerResource
```

## Properties

| Name | Description |
| --- | --- |
| [AntiAliasPolicy](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/antialiaspolicy/) { get; set; } | Gets or sets the anti alias policy of the placed layer in the PSD image. |
| [Bottom](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/bottom/) { get; set; } | Gets or sets the bottom location of the placed layer in the PSD image. |
| [Bounds](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/bounds/) { get; set; } | Gets or sets the bounds of the placed layer in the PSD file. |
| [HorizontalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/horizontalmeshpoints/) { get; set; } | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| [HorizontalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/horizontalmeshpointunit/) { get; set; } | Gets or sets the measure unit of the horizontal mesh points. |
| [IsCustom](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/iscustom/) { get; set; } | Gets or sets a value indicating whether this instance warp style is custom. If true it contains mesh points. If set to false it erases mesh points. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/items/) { get; set; } | Gets or sets the warp items. |
| [Left](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/left/) { get; set; } | Gets or sets the left location of the placed layer in the PSD file. |
| [PageNumber](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/pagenumber/) { get; set; } | Gets or sets the page number of the placed layer in the PSD file. |
| [Perspective](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/perspective/) { get; set; } | Gets or sets the perspective value of the placed layer in the PSD file. |
| [PerspectiveOther](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/perspectiveother/) { get; set; } | Gets or sets the perspective other value of the placed layer in the PSD file. |
| [PlacedLayerType](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/placedlayertype/) { get; set; } | Gets or sets the type of the placed layer in the PSD file. |
| [Right](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/right/) { get; set; } | Gets or sets the right location of the placed layer in the PSD file. |
| [Top](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/top/) { get; set; } | Gets or sets the top location of the placed layer in the PSD image. |
| [TotalPages](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/totalpages/) { get; set; } | Gets or sets the total pages of the placed layer in the PSD file. |
| [TransformMatrix](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/transformmatrix/) { get; set; } | Gets or sets the transform matrix of the placed layer in the PSD file. |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/uniqueid/) { get; set; } | Gets or sets the global unique identifier of the or smart object placed layer in the PSD image. |
| [UOrder](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/uorder/) { get; set; } | Gets or sets the U order value of the placed layer in the PSD file. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/value/) { get; set; } | Gets or sets the warp value of the placed layer in the PSD image. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/version/) { get; } | Gets the version of the placed layer in the PSD file, usually 3-5. |
| [VerticalMeshPoints](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/verticalmeshpoints/) { get; set; } | Gets or sets the horizontal mesh points of the placed layer in the PSD file. |
| [VerticalMeshPointUnit](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/verticalmeshpointunit/) { get; set; } | Gets or sets the measure unit of the vertical mesh points. |
| [VOrder](../../aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/vorder/) { get; set; } | Gets or sets the V order value of the placed layer in the PSD file. |

## Examples

The following code demonstrates the support of the SoLdResource resource.

```csharp
[C#]

// This example shows how to get or set the smart object layer data properties of the PSD file.

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
        0.0,
        0.0,
        0.0,
        0d,
        0d,
        149d,
        310d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        310d,
        149d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "d3388655-19e4-9742-82f2-f553bb01046a",
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
        0.0,
        0.0,
        0.0,
        0d,
        0d,
        721d,
        1280d,
        4,
        4,
        1,
        0,
        600,
        0,
        600,
        1,
        1280d,
        721d,
        72d,
        UnitTypes.Density,
        -1,
        -1,
        -1,
        "625cc4b9-2c5f-344f-8636-03caf2bd3489",
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
    SoLdResource resource = null;
    int index = 0;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            resource = imageResource as SoLdResource;
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

                AssertAreEqual(expectedValue[16], resource.Crop);
                AssertAreEqual(expectedValue[17], resource.FrameStepNumerator);
                AssertAreEqual(expectedValue[18], resource.FrameStepDenominator);
                AssertAreEqual(expectedValue[19], resource.DurationNumerator);
                AssertAreEqual(expectedValue[20], resource.DurationDenominator);
                AssertAreEqual(expectedValue[21], resource.FrameCount);
                AssertAreEqual(expectedValue[22], resource.Width);
                AssertAreEqual(expectedValue[23], resource.Height);
                AssertAreEqual(expectedValue[24], resource.Resolution);
                AssertAreEqual(expectedValue[25], resource.ResolutionUnit);
                AssertAreEqual(expectedValue[26], resource.Comp);
                AssertAreEqual(expectedValue[27], resource.CompId);
                AssertAreEqual(expectedValue[28], resource.OriginalCompId);
                AssertAreEqual(expectedValue[29], resource.PlacedId.ToString());
                AssertAreEqual((IEnumerable)expectedValue[30], resource.NonAffineTransformMatrix);
                if (resource.IsCustom)
                {
                    AssertAreEqual(expectedValue[31], resource.HorizontalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[32], resource.HorizontalMeshPoints);
                    AssertAreEqual(expectedValue[33], resource.VerticalMeshPointUnit);
                    AssertAreEqual((double[])expectedValue[34], resource.VerticalMeshPoints);
                    var temp = resource.VerticalMeshPoints;
                    resource.VerticalMeshPoints = resource.HorizontalMeshPoints;
                    resource.HorizontalMeshPoints = temp;
                }

                // This values should be changed in the PlLdResource (with the specified UniqueId) as well
                // and some of them must be in accord with the underlining smart object in the LinkDataSource
                resource.PageNumber = 2;
                resource.TotalPages = 3;
                resource.AntiAliasPolicy = 0;
                resource.Value = 1.23456789;
                resource.Perspective = 0.123456789;
                resource.PerspectiveOther = 0.987654321;
                resource.Top = -126;
                resource.Left = -215;
                resource.Bottom = 248;
                resource.Right = 145;
                resource.Crop = 4;
                resource.FrameStepNumerator = 1;
                resource.FrameStepDenominator = 601;
                resource.DurationNumerator = 2;
                resource.DurationDenominator = 602;
                resource.FrameCount = 11;
                resource.Width = 541;
                resource.Height = 249;
                resource.Resolution = 144;
                resource.Comp = 21;
                resource.CompId = 22;
                resource.TransformMatrix = new double[8]
                {
                    12.937922786050663,
                    19.419959734187131,
                    2.85445817782261,
                    1.0540625423957124,
                    7.20861031651307,
                    14.634102808208553,
                    17.292074924741144,
                    4
                };
                resource.NonAffineTransformMatrix = new double[8]
                {
                    129.937922786050663,
                    195.419959734187131,
                    26.85445817782261,
                    12.0540625423957124,
                    72.20861031651307,
                    147.634102808208553,
                    175.292074924741144,
                    42
                };

                // This unique Id should be changed in references if any
                resource.PlacedId = new Guid("12345678-9abc-def0-9876-54321fecba98");

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


