---
title: Class GaussianBlurSmartFilter
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.GaussianBlurSmartFilter classe. Le filtre intelligent GaussianBlur.
type: docs
weight: 3430
url: /fr/net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/
---
## GaussianBlurSmartFilter class

Le filtre intelligent GaussianBlur.

```csharp
public sealed class GaussianBlurSmartFilter : SmartFilter
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [GaussianBlurSmartFilter](gaussianblursmartfilter/)() | Initialise une nouvelle instance du`GaussianBlurSmartFilter` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Obtient ou définit le mode de fusion. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/filterid/) { get; } | Obtient l'identifiant du type de filtre intelligent. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Obtient ou définit l'état activé du filtre intelligent. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/name/) { get; } | Obtient le nom du filtre intelligent. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Obtient ou définit la valeur d'opacité du filtre intelligent. |
| [Radius](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/radius/) { get; set; } | Obtient ou définit le rayon du filtre intelligent gaussien. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | La structure du descripteur de source avec des données de filtre intelligentes. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Applique le filtre actuel à l'entrée[`RasterImage`](../../aspose.psd/rasterimage/) image. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Applique le filtre actuel à l'entrée[`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) données de masque. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Crée le clone par membre de l'instance actuelle du type. |

## Des champs

| Nom | La description |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/filtertype/) | L'identifiant du filtre intelligent actuel. |

### Exemples

Cet exemple illustre la prise en charge de l'interface des filtres intelligents.

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

    // édite les filtres intelligents
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // vérifie les valeurs du filtre
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // met à jour les valeurs du filtre
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // ajouter de nouveaux éléments de filtre
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // appliquer les modifications
    smartObj.SmartFilters.UpdateResourceValues();

    // Appliquer les filtres
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // vérifie les valeurs du filtre
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### Voir également

* class [SmartFilter](../smartfilter/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* Assemblée [Aspose.PSD](../../)


