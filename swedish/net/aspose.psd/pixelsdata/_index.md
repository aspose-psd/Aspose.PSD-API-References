---
title: "Klass PixelsData"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.PixelsData-klass. Klassen för att lagra bildpixeldata och dess gränser"
type: docs
weight: 5740
url: /sv/net/aspose.psd/pixelsdata/
---
{{< psd/tize >}}
## PixelsData class

Klassen för att lagra bildpixeldata och dess gränser.

```csharp
public sealed class PixelsData : ICloneable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PixelsData](pixelsdata/#constructor)() | Initierar en ny instans av `PixelsData`-klassen. |
| [PixelsData](pixelsdata/#constructor_1)(int[], Rectangle) | Initierar en ny instans av `PixelsData`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds/) { get; set; } | Hämtar eller anger gränserna för pixeldata. |
| [Pixels](../../aspose.psd/pixelsdata/pixels/) { get; set; } | Hämtar eller anger pixeldata. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../aspose.psd/pixelsdata/clone/)() | Den skapar en fullständig kopia av instansen |

## Exempel

Följande kod visar hur du skapar ett anpassat smart‑filter som har en anpassad renderare.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Initierar det ej stödda 'Crystallize'-smart‑filtret i inmatningsarrayen
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // det 'Crystallize'-smart‑filter‑ID:t.
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

        // Applicera filter på SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Applicera filter på lagermask
        smartFilter.ApplyToMask(maskLayer);

        //Applicera filter på lager
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
        // det 'Crystallize'-smart‑filter‑ID:t.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // hämta filterstruktur
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // hämta värdet för Crystallize‑storlek
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

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


