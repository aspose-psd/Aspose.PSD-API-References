---
title: "SharpenSmartFilter.FilterId"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "SharpenSmartFilter-Eigenschaft. Gibt den Typbezeichner des Smart-Filters zurück"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filterid/
---
{{< psd/tize >}}
## SharpenSmartFilter.FilterId property

Liefert den Typbezeichner des Smart-Filters.

```csharp
public override int FilterId { get; }
```

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

* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)


