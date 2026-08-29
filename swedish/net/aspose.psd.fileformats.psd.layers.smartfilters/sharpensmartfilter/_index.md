---
title: "Klass SharpenSmartFilter"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SharpenSmartFilter-klass. Det skarpa smartfiltret"
type: docs
weight: 3870
url: /sv/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter class

Det Sharpen smartfilter.

```csharp
public sealed class SharpenSmartFilter : SmartFilter
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SharpenSmartFilter](sharpensmartfilter/#constructor)() | Initierar en ny instans av klassen `SharpenSmartFilter`. |
| [SharpenSmartFilter](sharpensmartfilter/#constructor_1)(DescriptorStructure) | Initierar en ny instans av klassen `SharpenSmartFilter`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Hämtar eller anger blandningsläget. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filterid/) { get; } | Hämtar identifieraren för smartfiltertypen. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Hämtar eller anger om smartfiltret är aktiverat. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/name/) { get; } | Hämtar smartfilternamnet. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Hämtar eller anger opacitetsvärdet för smartfilter. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | Källbeskrivningsstrukturen med smartfilterdata. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Tillämpar det aktuella filtret på den inmatade [`RasterImage`](../../aspose.psd/rasterimage/) bilden. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Tillämpar det aktuella filtret på den inmatade [`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) maskdata. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Skapar en medlemsvis klon av den aktuella instansen av typen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filtertype/) | Identifieraren för det aktuella smartfiltret. |

## Exempel

Följande kod demonstrerar stöd för SharpenSmartFilter.

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

    // redigera smarta filter
    SharpenSmartFilter sharpen = (SharpenSmartFilter)smartObj.SmartFilters.Filters[0];

    // kontrollera filtervärden
    AssertAreEqual(BlendMode.Normal, sharpen.BlendMode);
    AssertAreEqual(100d, sharpen.Opacity);
    AssertAreEqual(true, sharpen.IsEnabled);

    // uppdatera filtervärden
    sharpen.BlendMode = BlendMode.Divide;
    sharpen.Opacity = 75;
    sharpen.IsEnabled = false;

    // lägg till nya filterobjekt
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new SharpenSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // tillämpa ändringar
    smartObj.SmartFilters.UpdateResourceValues();
    smartObj.UpdateModifiedContent();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Se även

* class [SmartFilter](../smartfilter/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


