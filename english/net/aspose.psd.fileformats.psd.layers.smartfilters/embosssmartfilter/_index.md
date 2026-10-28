---
title: Class EmbossSmartFilter
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.EmbossSmartFilter class. The Emboss smart filter
type: docs
weight: 3870
url: /net/aspose.psd.fileformats.psd.layers.smartfilters/embosssmartfilter/
---
{{< psd/tize >}}
## EmbossSmartFilter class

The Emboss smart filter.

```csharp
public sealed class EmbossSmartFilter : SmartFilter
```

## Constructors

| Name | Description |
| --- | --- |
| [EmbossSmartFilter](embosssmartfilter/)() | Initializes a new instance of the `EmbossSmartFilter` class. |

## Properties

| Name | Description |
| --- | --- |
| [Amount](../../aspose.psd.fileformats.psd.layers.smartfilters/embosssmartfilter/amount/) { get; set; } | Gets or sets the amount of emboss filter (percent). |
| [Angle](../../aspose.psd.fileformats.psd.layers.smartfilters/embosssmartfilter/angle/) { get; set; } | Gets or sets the angle of emboss filter (degrees, 0-360). |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Gets or sets the blending mode. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/embosssmartfilter/filterid/) { get; } | Gets the smart filter type identifier. |
| [Height](../../aspose.psd.fileformats.psd.layers.smartfilters/embosssmartfilter/height/) { get; set; } | Gets or sets the height of emboss filter (pixels). |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Gets or sets the is enabled status of the smart filter. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/embosssmartfilter/name/) { get; } | Gets the smart filter name. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Gets or sets the opacity value of smart filter. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | The source descriptor structure with smart filter data. |

## Methods

| Name | Description |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Applies the current filter to input [`RasterImage`](../../aspose.psd/rasterimage/) image. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Applies the current filter to input [`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) mask data. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Makes the memberwise clone of the current instance of the type. |

## Fields

| Name | Description |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/embosssmartfilter/filtertype/) | The identifier of current smart filter. |

## Examples

The following code demonstrates the support of Emboss smart filter.

```csharp
[C#]

string srcFileName = "no_filter.psd";
string sourceFile = srcFileName;
string outputFile = "out_PSDNET2834.psd";

using (var image = (PsdImage)Image.Load(sourceFile))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    EmbossSmartFilter emboss = new EmbossSmartFilter();
    emboss.Angle = 180;
    emboss.Height = 10;
    emboss.Amount = 120;
    filters.Add(emboss);
    smartObj.SmartFilters.Filters = filters.ToArray();
    smartObj.SmartFilters.UpdateResourceValues();

    image.Save(outputFile);
    // Check that output file can be opened by PS.
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];
    EmbossSmartFilter emboss = (EmbossSmartFilter)smartObj.SmartFilters.Filters[0];

    AssertAreEqual(180, emboss.Angle);
    AssertAreEqual(10, emboss.Height);
    AssertAreEqual(120, emboss.Amount);
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


