---
title: "Classe SharpenSmartFilter"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SharpenSmartFilter class. Le filtre intelligent Sharpen"
type: docs
weight: 3870
url: /fr/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter class

Le filtre intelligent Sharpen.

```csharp
public sealed class SharpenSmartFilter : SmartFilter
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SharpenSmartFilter](sharpensmartfilter/#constructor)() | Initialise une nouvelle instance de la classe `SharpenSmartFilter`. |
| [SharpenSmartFilter](sharpensmartfilter/#constructor_1)(DescriptorStructure) | Initialise une nouvelle instance de la classe `SharpenSmartFilter`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Obtient ou définit le mode de fusion. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filterid/) { get; } | Obtient l'identifiant du type de filtre intelligent. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Obtient ou définit le statut d'activation du filtre intelligent. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/name/) { get; } | Obtient le nom du filtre intelligent. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Obtient ou définit la valeur d'opacité du filtre intelligent. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | La structure du descripteur source contenant les données du filtre intelligent. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Applique le filtre actuel à l'image d'entrée [`RasterImage`](../../aspose.psd/rasterimage/). |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Applique le filtre actuel aux données de masque d'entrée [`Layer`](../../aspose.psd.fileformats.psd.layers/layer/). |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Crée le clone membre par membre de l'instance actuelle du type. |

## Champs

| Nom | Description |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filtertype/) | L'identifiant du filtre intelligent actuel. |

## Exemples

Le code suivant montre la prise en charge de SharpenSmartFilter.

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

    // modifier les filtres intelligents
    SharpenSmartFilter sharpen = (SharpenSmartFilter)smartObj.SmartFilters.Filters[0];

    // vérifier les valeurs du filtre
    AssertAreEqual(BlendMode.Normal, sharpen.BlendMode);
    AssertAreEqual(100d, sharpen.Opacity);
    AssertAreEqual(true, sharpen.IsEnabled);

    // mettre à jour les valeurs du filtre
    sharpen.BlendMode = BlendMode.Divide;
    sharpen.Opacity = 75;
    sharpen.IsEnabled = false;

    // ajouter de nouveaux éléments de filtre
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new SharpenSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // appliquer les modifications
    smartObj.SmartFilters.UpdateResourceValues();
    smartObj.UpdateModifiedContent();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Voir aussi

* class [SmartFilter](../smartfilter/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


