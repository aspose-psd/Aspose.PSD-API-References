---
title: "SharpenSmartFilter.FilterType"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "SharpenSmartFilter veld. De identificatie van de huidige slimme filter"
type: docs
weight: 40
url: /nl/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filtertype/
---
{{< psd/tize >}}
## SharpenSmartFilter.FilterType field

De identificatie van de huidige smart filter.

```csharp
public const int FilterType;
```

## Voorbeelden

De volgende code demonstreert de ondersteuning van SharpenSmartFilter.

```csharp
[C#]

string sourceFile = "sharpen_source.psd";
string outputPsd = "sharpen_output.psd";
string outputPng = "sharpen_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFile))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // bewerk smart filters
    SharpenSmartFilter sharpen = (SharpenSmartFilter)smartObj.SmartFilters.Filters[0];

    // controleer filterwaarden
    AssertAreEqual(BlendMode.Normal, sharpen.BlendMode);
    AssertAreEqual(100d, sharpen.Opacity);
    AssertAreEqual(true, sharpen.IsEnabled);

    // werk filterwaarden bij
    sharpen.BlendMode = BlendMode.Divide;
    sharpen.Opacity = 75;
    sharpen.IsEnabled = false;

    // voeg nieuwe filteritems toe
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new SharpenSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // pas wijzigingen toe
    smartObj.SmartFilters.UpdateResourceValues();
    smartObj.UpdateModifiedContent();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Zie ook

* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)


