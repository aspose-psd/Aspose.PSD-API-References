---
title: "PixelsData.PixelsData"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur PixelsData. Initialise une nouvelle instance de la classe PixelsData"
type: docs
weight: 10
url: /fr/net/aspose.psd/pixelsdata/pixelsdata/
---
{{< psd/tize >}}
## PixelsData() {#constructor}

Initialise une nouvelle instance de la classe [`PixelsData`](../).

```csharp
public PixelsData()
```

## Exemples

Le code suivant vous montre comment créer un filtre intelligent personnalisé qui possède un rendu personnalisé.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Initialise le filtre intelligent non pris en charge 'Crystallize' dans le tableau d'entrée
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

        // Appliquer le filtre à SmartObject
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
        // obtenir la structure du filtre
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // obtenir la valeur de la taille Crystallize
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

### Voir aussi

* class [PixelsData](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## PixelsData(int[], Rectangle) {#constructor_1}

Initialise une nouvelle instance de la classe [`PixelsData`](../).

```csharp
public PixelsData(int[] pixels, Rectangle bounds)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | Int32[] | Les données de pixels. |
| limites | Rectangle | Le rectangle des limites des pixels. |

## Exemples

Le code suivant vous montre comment créer un filtre intelligent personnalisé qui possède un rendu personnalisé.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Initialise le filtre intelligent non pris en charge 'Crystallize' dans le tableau d'entrée
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

        // Appliquer le filtre à SmartObject
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
        // obtenir la structure du filtre
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // obtenir la valeur de la taille Crystallize
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

### Voir aussi

* struct [Rectangle](../../rectangle/)
* class [PixelsData](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


