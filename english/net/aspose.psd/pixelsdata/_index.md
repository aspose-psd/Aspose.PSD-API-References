---
title: Class PixelsData
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.PixelsData class. The class to store image pixels data and its bounds
type: docs
weight: 5610
url: /net/aspose.psd/pixelsdata/
---
{{< psd/tize >}}
## PixelsData class

The class to store image pixels data and its bounds.

```csharp
public sealed class PixelsData
```

## Constructors

| Name | Description |
| --- | --- |
| [PixelsData](pixelsdata/#constructor)() | Initializes a new instance of the `PixelsData` class. |
| [PixelsData](pixelsdata/#constructor_1)(int[], Rectangle) | Initializes a new instance of the `PixelsData` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds/) { get; set; } | Gets or sets the bounds of pixels data. |
| [Pixels](../../aspose.psd/pixelsdata/pixels/) { get; set; } | Gets or sets the pixels data. |

## Examples

The following code shows you how to create a custom smart filter that has a custom renderer.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Inits the unsupported 'Crystallize' smart filter at input array
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // the 'Crystallize' smart filter ID.
        int id = 1131574132;

        for (int i = 0; i < smartFilters.Length; i++)
        {
            var smartFilter = smartFilters[i];
            if (smartFilter is UnknownSmartFilter && smartFilter.FilterId == id)
            {
                var customSmartFilterInstance = new CustomSmartFilterWithRenderer();
                customSmartFilterInstance.SourceDescriptor.Structures = smartFilter.SourceDescriptor.Structures;
                smartFilters[i] = customSmartFilterInstance;
            }
        }

        return smartFilters;
    }

    using (var image = (PsdImage) Image.Load(sourceFile))
    {
        SmartObjectLayer smartLayer = (SmartObjectLayer) image.Layers[1];
        Layer maskLayer = image.Layers[2];
        Layer regularLayer = image.Layers[3];

        smartLayer.SmartFilters.Filters = InitUnknownSmartFilters(smartLayer.SmartFilters.Filters);
        var smartFilter = smartLayer.SmartFilters.Filters[0];

        // Apply filter to SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Apply filter to layer mask
        smartFilter.ApplyToMask(maskLayer);

        //Apply filter to layer
        smartFilter.Apply(regularLayer);

        image.Save(outputPsd);
        image.Save(outputPng, new PngOptions());
    }
}

public sealed class CustomSmartFilterWithRenderer : SmartFilter, ISmartFilterRenderer
{
    public override string Name
    {
        get { return "Custom 'Crystallize' smart filter\0"; }
    }

    public override int FilterId
    {
        // the 'Crystallize' smart filter ID.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // get filter structure
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // get value of Crystallize Size
        var valueStructure = (IntegerStructure) filterDescriptor.Structures[0];

        for (int i = 0; i < pixelsData.Pixels.Length; i++)
        {
            if (i % valueStructure.Value == 0)
            {
                pixelsData.Pixels[i] = 0;
            }
        }

        return pixelsData;
    }
}
```

### See Also

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


