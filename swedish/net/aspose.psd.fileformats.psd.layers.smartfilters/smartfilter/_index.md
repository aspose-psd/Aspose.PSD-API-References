---
title: Class SmartFilter
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SmartFilter klass. Klassen för att bearbeta en baslogik av smarta filter.
type: docs
weight: 3460
url: /sv/net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/
---
## SmartFilter class

Klassen för att bearbeta en baslogik av smarta filter.

```csharp
public abstract class SmartFilter : ICloneable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [SmartFilter](smartfilter/)() | Initierar en ny instans av`SmartFilter` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Hämtar eller ställer in blandningsläget. |
| abstract [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/filterid/) { get; } | Hämtar den smarta filtertypidentifieraren. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Hämtar eller ställer in statusen är aktiverad för det smarta filtret. |
| abstract [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/name/) { get; } | Får det smarta filternamnet. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Hämtar eller ställer in opacitetsvärdet för smart filter. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | Källbeskrivningsstrukturen med smarta filterdata. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Tillämpar det aktuella filtret på indata[`RasterImage`](../../aspose.psd/rasterimage/) bild. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Tillämpar det aktuella filtret på indata[`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) mask data. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Gör den medlemsvisa klonen av den aktuella instansen av typen. |

### Exempel

Det här exemplet visar stödet för gränssnittet för smarta filter.

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

    // redigera smarta filter
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // kontrollera filtervärden
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // uppdatera filtervärden
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // lägg till nya filterobjekt
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // applicera förändringar
    smartObj.SmartFilters.UpdateResourceValues();

    // Använd filter
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // kontrollera filtervärden
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### Se även

* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* hopsättning [Aspose.PSD](../../)


