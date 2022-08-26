---
title: PixelsData
second_title: Référence de l'API Aspose.PSD pour .NET
description: Initialise une nouvelle instance duPixelsDataaspose.psd/pixelsdata classe.
type: docs
weight: 10
url: /fr/net/aspose.psd/pixelsdata/pixelsdata/
---
## PixelsData() {#constructor}

Initialise une nouvelle instance du[`PixelsData`](../../pixelsdata) classe.

```csharp
public PixelsData()
```

### Exemples

Le code suivant vous montre comment créer un filtre intelligent personnalisé avec un rendu personnalisé.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Initialise le filtre intelligent 'Crystallize' non pris en charge au niveau du tableau d'entrée
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // l'ID du filtre intelligent 'Crystallize'.
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

        // Appliquer le filtre au SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Appliquer le filtre au masque de calque
        smartFilter.ApplyToMask(maskLayer);

        //Appliquer le filtre au calque
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
        // l'ID du filtre intelligent 'Crystallize'.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // récupère la structure du filtre
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // récupère la valeur de Crystallize Size
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

### Voir également

* class [PixelsData](../../pixelsdata)
* espace de noms [Aspose.PSD](../../pixelsdata)
* Assemblée [Aspose.PSD](../../../)

---

## PixelsData(int[], Rectangle) {#constructor_1}

Initialise une nouvelle instance du[`PixelsData`](../../pixelsdata) classe.

```csharp
public PixelsData(int[] pixels, Rectangle bounds)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pixels | Int32[] | Les données de pixels. |
| bounds | Rectangle | Le rectangle de délimitation des pixels. |

### Exemples

Le code suivant vous montre comment créer un filtre intelligent personnalisé avec un rendu personnalisé.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Initialise le filtre intelligent 'Crystallize' non pris en charge au niveau du tableau d'entrée
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // l'ID du filtre intelligent 'Crystallize'.
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

        // Appliquer le filtre au SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Appliquer le filtre au masque de calque
        smartFilter.ApplyToMask(maskLayer);

        //Appliquer le filtre au calque
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
        // l'ID du filtre intelligent 'Crystallize'.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // récupère la structure du filtre
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // récupère la valeur de Crystallize Size
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

### Voir également

* struct [Rectangle](../../rectangle)
* class [PixelsData](../../pixelsdata)
* espace de noms [Aspose.PSD](../../pixelsdata)
* Assemblée [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
