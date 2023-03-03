---
title: Class PixelsData
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.PixelsData classe. La classe per memorizzare i dati dei pixel dellimmagine e i relativi limiti.
type: docs
weight: 5250
url: /it/net/aspose.psd/pixelsdata/
---
## PixelsData class

La classe per memorizzare i dati dei pixel dell'immagine e i relativi limiti.

```csharp
public sealed class PixelsData
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PixelsData](pixelsdata/#constructor)() | Inizializza una nuova istanza di`PixelsData` classe. |
| [PixelsData](pixelsdata/#constructor_1)(int[], Rectangle) | Inizializza una nuova istanza di`PixelsData` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bounds](../../aspose.psd/pixelsdata/bounds/) { get; set; } | Ottiene o imposta i limiti dei dati in pixel. |
| [Pixels](../../aspose.psd/pixelsdata/pixels/) { get; set; } | Ottiene o imposta i dati dei pixel. |

### Esempi

Il codice seguente mostra come creare un filtro avanzato personalizzato con un renderer personalizzato.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Avvia il filtro intelligente "Crystallize" non supportato nell'array di input
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // l'ID del filtro intelligente "Crystallize".
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

        // Applica il filtro a SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Applica il filtro alla maschera di livello
        smartFilter.ApplyToMask(maskLayer);

        //Applica filtro al livello
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
        // l'ID del filtro intelligente "Crystallize".
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // ottiene la struttura del filtro
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // ottiene il valore di Crystallize Size
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

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


