---
title: "Klasse PixelsData"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.PixelsData‑Klasse. Die Klasse zum Speichern von Bildpixel‑Daten und deren Grenzen"
type: docs
weight: 5740
url: /de/net/aspose.psd/pixelsdata/
---
{{< psd/tize >}}
## PixelsData class

Die Klasse zum Speichern von Bildpixeldaten und deren Begrenzungen.

```csharp
public sealed class PixelsData : ICloneable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PixelsData](pixelsdata/#constructor)() | Initialisiert eine neue Instanz der `PixelsData`‑Klasse. |
| [PixelsData](pixelsdata/#constructor_1)(int[], Rectangle) | Initialisiert eine neue Instanz der `PixelsData`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds/) { get; set; } | Ermittelt oder legt die Grenzen der Pixel‑Daten fest. |
| [Pixels](../../aspose.psd/pixelsdata/pixels/) { get; set; } | Ermittelt oder legt die Pixel‑Daten fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clone](../../aspose.psd/pixelsdata/clone/)() | Erstellt eine vollständige Kopie der Instanz |

## Beispiele

Der folgende Code zeigt, wie man einen benutzerdefinierten Smart-Filter erstellt, der einen benutzerdefinierten Renderer hat.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Initialisiert den nicht unterstützten 'Crystallize'-Smart-Filter im Eingabearray
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // die 'Crystallize'-Smart-Filter-ID.
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

        // Filter auf SmartObject anwenden
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Filter auf Ebenenmaske anwenden
        smartFilter.ApplyToMask(maskLayer);

        //Filter auf Ebene anwenden
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
        // die 'Crystallize'-Smart-Filter-ID.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // Filterstruktur abrufen
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // Wert von Crystallize Size abrufen
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

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


