---
title: Enum UndefinedAreas
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.UndefinedAreas enum. Undefined areas enumeration
type: docs
weight: 3930
url: /net/aspose.psd.fileformats.psd.layers.smartfilters/undefinedareas/
---
{{< psd/tize >}}
## UndefinedAreas enumeration

Undefined areas enumeration.

```csharp
public enum UndefinedAreas
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| RepeatEdgePixels | `0` | Repeat edge. |
| WrapAround | `1` | Repeat areas. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


