---
title: AddNoiseSmartFilter
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Il filtro intelligente AddNoise.
type: docs
weight: 3360
url: /it/net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/
---
## AddNoiseSmartFilter class

Il filtro intelligente AddNoise.

```csharp
public sealed class AddNoiseSmartFilter : SmartFilter
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [AddNoiseSmartFilter](addnoisesmartfilter)() | Inizializza una nuova istanza di[`AddNoiseSmartFilter`](../addnoisesmartfilter) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AmountNoise](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/amountnoise) { get; set; } | Ottiene o imposta la quantità del valore di disturbo. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode) { get; set; } | Ottiene o imposta la modalità di fusione. |
| [Distribution](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/distribution) { get; set; } | Ottiene o imposta la distribuzione del filtro del rumore. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/filterid) { get; } | Ottiene l'identificatore del tipo di filtro intelligente. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled) { get; set; } | Ottiene o imposta lo stato è abilitato del filtro intelligente. |
| [IsMonochromatic](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/ismonochromatic) { get; set; } | Ottiene o imposta il valore di monocromatico. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/name) { get; } | Ottiene il nome del filtro intelligente. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity) { get; set; } | Ottiene o imposta il valore di opacità del filtro intelligente. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor) { get; } | La struttura del descrittore di origine con i dati del filtro intelligente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply)(RasterImage) | Applica il filtro corrente all'input[`RasterImage`](../../aspose.psd/rasterimage) immagine. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask)(Layer) | Applica il filtro corrente all'input[`Layer`](../../aspose.psd.fileformats.psd.layers/layer) dati maschera. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone)() | Crea il clone a livello di membro dell'istanza corrente del tipo. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/filtertype) | L'identificatore del filtro intelligente corrente. |

### Esempi

Questo esempio mostra il supporto dell'interfaccia dei filtri intelligenti.

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

    // modifica i filtri intelligenti
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // controlla i valori del filtro
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // aggiorna i valori del filtro
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // aggiungi nuovi elementi filtro
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // applica i cambiamenti
    smartObj.SmartFilters.UpdateResourceValues();

    // Applica filtri
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // controlla i valori del filtro
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### Guarda anche

* class [SmartFilter](../smartfilter)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
