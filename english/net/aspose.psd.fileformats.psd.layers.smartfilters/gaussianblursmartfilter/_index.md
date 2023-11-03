---
title: Class GaussianBlurSmartFilter
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.GaussianBlurSmartFilter class. The GaussianBlur smart filter
type: docs
weight: 3630
url: /net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/
---
{{< psd/tize >}}
## GaussianBlurSmartFilter class

The GaussianBlur smart filter.

```csharp
public sealed class GaussianBlurSmartFilter : SmartFilter
```

## Constructors

| Name | Description |
| --- | --- |
| [GaussianBlurSmartFilter](gaussianblursmartfilter/)() | Initializes a new instance of the `GaussianBlurSmartFilter` class. |

## Properties

| Name | Description |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Gets or sets the blending mode. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/filterid/) { get; } | Gets the smart filter type identifier. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Gets or sets the is enabled status of the smart filter. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/name/) { get; } | Gets the smart filter name. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Gets or sets the opacity value of smart filter. |
| [Radius](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/radius/) { get; set; } | Gets or sets the radius of gaussian smart filter. |
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
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/filtertype/) | The identifier of current smart filter. |

## Examples

This example demonstrates the support of the smart filters interface.

```csharp
[C#]

string sourceFilte = "r2_SmartFilters.psd";
string outputPsd = "out_r2_SmartFilters.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFilte))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // edit smart filters
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // check filter values
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // update filter values
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // add new filter items
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // apply changes
    smartObj.SmartFilters.UpdateResourceValues();

    // Apply filters
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // check filter values
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### See Also

* class [SmartFilter](../smartfilter/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


