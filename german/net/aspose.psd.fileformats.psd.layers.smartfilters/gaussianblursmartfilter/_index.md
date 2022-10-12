---
title: GaussianBlurSmartFilter
second_title: Aspose.PSD für .NET-API-Referenz
description: Der intelligente GaußianBlurFilter.
type: docs
weight: 3370
url: /de/net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/
---
## GaussianBlurSmartFilter class

Der intelligente GaußianBlur-Filter.

```csharp
public sealed class GaussianBlurSmartFilter : SmartFilter
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [GaussianBlurSmartFilter](gaussianblursmartfilter)() | Initialisiert eine neue Instanz von[`GaussianBlurSmartFilter`](../gaussianblursmartfilter) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode) { get; set; } | Ruft den Mischmodus ab oder legt ihn fest. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/filterid) { get; } | Ruft die Kennung des intelligenten Filtertyps ab. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled) { get; set; } | Ruft den aktivierten Status des intelligenten Filters ab oder legt ihn fest. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/name) { get; } | Ruft den Namen des intelligenten Filters ab. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity) { get; set; } | Ruft den Deckkraftwert des Smartfilters ab oder legt ihn fest. |
| [Radius](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/radius) { get; set; } | Ruft den Radius des Gaußschen Smart-Filters ab oder legt ihn fest. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor) { get; } | Die Quelldeskriptorstruktur mit intelligenten Filterdaten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply)(RasterImage) | Wendet den aktuellen Filter auf die Eingabe an[`RasterImage`](../../aspose.psd/rasterimage) Bild. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask)(Layer) | Wendet den aktuellen Filter auf die Eingabe an[`Layer`](../../aspose.psd.fileformats.psd.layers/layer) Maskendaten. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone)() | Erstellt den mitgliederweisen Klon der aktuellen Instanz des Typs. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/filtertype) | Die Kennung des aktuellen Smartfilters. |

### Beispiele

Dieses Beispiel demonstriert die Unterstützung der Schnittstelle für intelligente Filter.

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

    // intelligente Filter bearbeiten
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // Filterwerte prüfen
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // Filterwerte aktualisieren
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // neue Filterelemente hinzufügen
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // Änderungen übernehmen
    smartObj.SmartFilters.UpdateResourceValues();

    // Filter anwenden
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // Filterwerte prüfen
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### Siehe auch

* class [SmartFilter](../smartfilter)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
