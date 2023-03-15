---
title: Interface ISmartFilterRenderer
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering.ISmartFilterRenderer interface. Linterface pour un rendu de filtre intelligent spécifique.
type: docs
weight: 3450
url: /fr/net/aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/
---
## ISmartFilterRenderer interface

L'interface pour un rendu de filtre intelligent spécifique.

```csharp
public interface ISmartFilterRenderer
```

## Méthodes

| Nom | La description |
| --- | --- |
| [Render](../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/render/)(PixelsData) | Rend le filtre intelligent actuel sur les données de pixels. |

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

* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering](../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/)
* Assemblée [Aspose.PSD](../../)


