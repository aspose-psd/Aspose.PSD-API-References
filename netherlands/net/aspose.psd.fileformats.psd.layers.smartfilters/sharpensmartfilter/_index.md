---
title: "Class SharpenSmartFilter"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SharpenSmartFilter class. De Sharpen smart filter"
type: docs
weight: 3870
url: /nl/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter class

De Sharpen smart filter.

```csharp
public sealed class SharpenSmartFilter : SmartFilter
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SharpenSmartFilter](sharpensmartfilter/#constructor)() | Initialiseert een nieuw exemplaar van de `SharpenSmartFilter` class. |
| [SharpenSmartFilter](sharpensmartfilter/#constructor_1)(DescriptorStructure) | Initialiseert een nieuw exemplaar van de `SharpenSmartFilter` class. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Haalt op of stelt de mengmodus in. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filterid/) { get; } | Haalt de type‑identificatie van de smart filter op. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Haalt op of stelt de ingeschakelde status van de smart filter in. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/name/) { get; } | Haalt de naam van de smart filter op. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Haalt op of stelt de opaciteitswaarde van de smart filter in. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | De bron‑descriptorstructuur met smart filter‑gegevens. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Past het huidige filter toe op de invoer‑[`RasterImage`](../../aspose.psd/rasterimage/) afbeelding. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Past het huidige filter toe op de invoer‑[`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) maskergegevens. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Maakt de lid‑voor‑lid kloon van de huidige instantie van het type. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filtertype/) | De identificatie van de huidige smart filter. |

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

* class [SmartFilter](../smartfilter/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


