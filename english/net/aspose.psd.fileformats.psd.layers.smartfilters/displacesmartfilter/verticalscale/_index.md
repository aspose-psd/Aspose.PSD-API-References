---
title: DisplaceSmartFilter.VerticalScale
second_title: Aspose.PSD for .NET API Reference
description: DisplaceSmartFilter property. Gets or sets the vertical scale percent
type: docs
weight: 100
url: /net/aspose.psd.fileformats.psd.layers.smartfilters/displacesmartfilter/verticalscale/
---
{{< psd/tize >}}
## DisplaceSmartFilter.VerticalScale property

Gets or sets the vertical scale (percent).

```csharp
public double VerticalScale { get; set; }
```

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

* class [DisplaceSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)


