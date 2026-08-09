---
title: "Klasse SharpenSmartFilter"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SharpenSmartFilter class. Der Schärfen‑Smart‑Filter"
type: docs
weight: 3870
url: /de/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter class

Der Schärfen‑Smart‑Filter.

```csharp
public sealed class SharpenSmartFilter : SmartFilter
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SharpenSmartFilter](sharpensmartfilter/#constructor)() | Initialisiert eine neue Instanz der `SharpenSmartFilter`‑Klasse. |
| [SharpenSmartFilter](sharpensmartfilter/#constructor_1)(DescriptorStructure) | Initialisiert eine neue Instanz der `SharpenSmartFilter`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Liefert oder setzt den Mischmodus. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filterid/) { get; } | Liefert den Typbezeichner des Smart-Filters. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Liefert oder setzt den aktivierten Status des Smart-Filters. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/name/) { get; } | Liefert den Namen des Smart-Filters. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Liefert oder setzt den Deckkraftwert des Smart-Filters. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | Die Quell-Deskriptor-Struktur mit Smart-Filter-Daten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Wendet den aktuellen Filter auf das Eingabe-[`RasterImage`](../../aspose.psd/rasterimage/) Bild an. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Wendet den aktuellen Filter auf die Eingabe-[`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) Maskendaten an. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Erstellt die Mitgliedskopie der aktuellen Instanz des Typs. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filtertype/) | Der Bezeichner des aktuellen Smart-Filters. |

## Beispiele

Der folgende Code demonstriert die Unterstützung von SharpenSmartFilter.

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

    // Smart-Filter bearbeiten
    SharpenSmartFilter sharpen = (SharpenSmartFilter)smartObj.SmartFilters.Filters[0];

    // Filterwerte prüfen
    AssertAreEqual(BlendMode.Normal, sharpen.BlendMode);
    AssertAreEqual(100d, sharpen.Opacity);
    AssertAreEqual(true, sharpen.IsEnabled);

    // Filterwerte aktualisieren
    sharpen.BlendMode = BlendMode.Divide;
    sharpen.Opacity = 75;
    sharpen.IsEnabled = false;

    // Neue Filterelemente hinzufügen
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new SharpenSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // Änderungen anwenden
    smartObj.SmartFilters.UpdateResourceValues();
    smartObj.UpdateModifiedContent();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Siehe auch

* class [SmartFilter](../smartfilter/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


