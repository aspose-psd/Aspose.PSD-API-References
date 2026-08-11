---
title: "SharpenSmartFilter.Name"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà SharpenSmartFilter. Ottiene il nome del filtro intelligente"
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/name/
---
{{< psd/tize >}}
## SharpenSmartFilter.Name property

Ottiene il nome del filtro intelligente.

```csharp
public override string Name { get; }
```

## Esempi

Il codice seguente dimostra il supporto di SharpenSmartFilter.

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

    // modifica filtri intelligenti
    SharpenSmartFilter sharpen = (SharpenSmartFilter)smartObj.SmartFilters.Filters[0];

    // controlla i valori del filtro
    AssertAreEqual(BlendMode.Normal, sharpen.BlendMode);
    AssertAreEqual(100d, sharpen.Opacity);
    AssertAreEqual(true, sharpen.IsEnabled);

    // aggiorna i valori del filtro
    sharpen.BlendMode = BlendMode.Divide;
    sharpen.Opacity = 75;
    sharpen.IsEnabled = false;

    // aggiungi nuovi elementi filtro
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new SharpenSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // applica le modifiche
    smartObj.SmartFilters.UpdateResourceValues();
    smartObj.UpdateModifiedContent();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Vedi anche

* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)


