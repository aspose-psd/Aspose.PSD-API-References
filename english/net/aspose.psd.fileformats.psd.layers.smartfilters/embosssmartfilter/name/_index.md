---
title: EmbossSmartFilter.Name
second_title: Aspose.PSD for .NET API Reference
description: EmbossSmartFilter property. Gets the smart filter name
type: docs
weight: 60
url: /net/aspose.psd.fileformats.psd.layers.smartfilters/embosssmartfilter/name/
---
{{< psd/tize >}}
## EmbossSmartFilter.Name property

Gets the smart filter name.

```csharp
public override string Name { get; }
```

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

* class [EmbossSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)


