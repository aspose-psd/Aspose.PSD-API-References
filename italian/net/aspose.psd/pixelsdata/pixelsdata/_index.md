---
title: PixelsData.PixelsData
second_title: Aspose.PSD per riferimento API .NET
description: PixelsData costruttore. Inizializza una nuova istanza diPixelsData classe.
type: docs
weight: 10
url: /it/net/aspose.psd/pixelsdata/pixelsdata/
---
## PixelsData() {#constructor}

Inizializza una nuova istanza di[`PixelsData`](../) classe.

```csharp
public PixelsData()
```

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

* class [PixelsData](../)
* spazio dei nomi [Aspose.PSD](../../pixelsdata/)
* assemblea [Aspose.PSD](../../../)

---

## PixelsData(int[], Rectangle) {#constructor_1}

Inizializza una nuova istanza di[`PixelsData`](../) classe.

```csharp
public PixelsData(int[] pixels, Rectangle bounds)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | Int32[] | I dati dei pixel. |
| bounds | Rectangle | Il pixel limita il rettangolo. |

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

* struct [Rectangle](../../rectangle/)
* class [PixelsData](../)
* spazio dei nomi [Aspose.PSD](../../pixelsdata/)
* assemblea [Aspose.PSD](../../../)


