---
title: Class PixelsData
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.PixelsData klas. De klasse om afbeeldingspixelgegevens en de grenzen ervan op te slaan.
type: docs
weight: 5250
url: /nl/net/aspose.psd/pixelsdata/
---
## PixelsData class

De klasse om afbeeldingspixelgegevens en de grenzen ervan op te slaan.

```csharp
public sealed class PixelsData
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PixelsData](pixelsdata/#constructor)() | Initialiseert een nieuw exemplaar van het`PixelsData` klasse. |
| [PixelsData](pixelsdata/#constructor_1)(int[], Rectangle) | Initialiseert een nieuw exemplaar van het`PixelsData` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds/) { get; set; } | Haalt de grenzen van pixelgegevens op of stelt deze in. |
| [Pixels](../../aspose.psd/pixelsdata/pixels/) { get; set; } | Haalt of stelt de pixelgegevens in. |

### Voorbeelden

De volgende code laat zien hoe u een aangepast slim filter maakt met een aangepaste renderer.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Start het niet-ondersteunde slimme filter 'Crystallize' in de invoerarray
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // de 'Crystallize' slimme filter-ID.
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

        // Filter toepassen op SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Filter toepassen op laagmasker
        smartFilter.ApplyToMask(maskLayer);

        // Pas filter toe op laag
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
        // de 'Crystallize' slimme filter-ID.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // krijg filterstructuur
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // haal de waarde van Crystallize Size op
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

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


