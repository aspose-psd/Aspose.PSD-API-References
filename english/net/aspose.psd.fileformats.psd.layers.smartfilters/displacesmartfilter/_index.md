---
title: Class DisplaceSmartFilter
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.DisplaceSmartFilter class. The Displace smart filter
type: docs
weight: 3840
url: /net/aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/
---
{{< psd/tize >}}
## DisplaceSmartFilter class

The Displace smart filter.

```csharp
public sealed class DisplaceSmartFilter : SmartFilter
```

## Constructors

| Name | Description |
| --- | --- |
| [DisplaceSmartFilter](displacesmartfilter/)(string, bool) | Initializes a new instance of the `DisplaceSmartFilter` class. |

## Properties

| Name | Description |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Gets or sets the blending mode. |
| [DisplaceMapData](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/displacemapdata/) { get; } | Gets or sets the embedded displacement map data (DspD). |
| [DisplacementMapPath](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/displacementmappath/) { get; } | Gets the displacement map full path extracted from the DspF structure, or null if not found. |
| [DisplacementMethod](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/displacementmethod/) { get; set; } | Gets or sets the displacement method. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/filterid/) { get; } | Gets the smart filter type identifier. |
| [HorizontalScale](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/horizontalscale/) { get; set; } | Gets or sets the horizontal scale (percent). |
| [IsDisplacementMapEmbedded](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/isdisplacementmapembedded/) { get; } | Gets or sets the embedded flag (EmbF) value. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Gets or sets the is enabled status of the smart filter. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/name/) { get; } | Gets the smart filter name. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Gets or sets the opacity value of smart filter. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | The source descriptor structure with smart filter data. |
| [UndefinedAreas](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/undefinedareas/) { get; set; } | Gets or sets the missing file handling method. |
| [VerticalScale](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/verticalscale/) { get; set; } | Gets or sets the vertical scale (percent). |

## Methods

| Name | Description |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Applies the current filter to input [`RasterImage`](../../aspose.psd/rasterimage/) image. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Applies the current filter to input [`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) mask data. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Makes the memberwise clone of the current instance of the type. |

## Fields

| Name | Description |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/filtertype/) | The identifier of current smart filter (class ID "Dspl"). |

## Examples

The following code demonstrates the support of DisplaceSmartFilter.

```csharp
[C#]

string srcFileName = "no_displace_filter.psd";
string sourceFile = srcFileName;
string outputFile = "output_displace_filter.psd";
string displaceMapPath = "displace_map.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];
    DisplaceSmartFilter displace = new DisplaceSmartFilter(displaceMapPath, true)
    {
        HorizontalScale = 12.5,
        VerticalScale = 15.0,
        DisplacementMethod = DisplacementMethod.Tile,
        UndefinedAreas = UndefinedAreas.WrapAround
    };

    List<SmartFilter> filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(displace);
    smartObj.SmartFilters.Filters = filters.ToArray();
    smartObj.SmartFilters.UpdateResourceValues();
    image.Save(outputFile);

    // Need to check that output psd file can be opened by Photoshop
}

using (PsdImage image = (PsdImage)Image.Load(outputFile))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];
    DisplaceSmartFilter displace = smartObj.SmartFilters
        .Filters[smartObj.SmartFilters.Filters.Length - 1] as DisplaceSmartFilter;

    AssertAreEqual(12.5, displace.HorizontalScale);
    AssertAreEqual(15.0, displace.VerticalScale);
    AssertAreEqual(DisplacementMethod.Tile, displace.DisplacementMethod);
    AssertAreEqual(UndefinedAreas.WrapAround, displace.UndefinedAreas);
    AssertAreEqual(true, displace.IsDisplacementMapEmbedded);
    AssertAreEqual(true, displace.DisplaceMapData != null);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### See Also

* class [SmartFilter](../smartfilter/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


