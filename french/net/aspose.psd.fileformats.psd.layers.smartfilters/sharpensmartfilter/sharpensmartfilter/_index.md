---
title: "SharpenSmartFilter.SharpenSmartFilter"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur SharpenSmartFilter. Initialise une nouvelle instance de la classe SharpenSmartFilter"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter() {#constructor}

Initialise une nouvelle instance de la classe [`SharpenSmartFilter`](../).

```csharp
public SharpenSmartFilter()
```

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

* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)

---

## SharpenSmartFilter(DescriptorStructure) {#constructor_1}

Initialise une nouvelle instance de la classe [`SharpenSmartFilter`](../).

```csharp
public SharpenSmartFilter(DescriptorStructure sourceDescriptor)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceDescriptor | DescriptorStructure | La structure du descripteur avec les informations du filtre intelligent. |

### Voir aussi

* class [DescriptorStructure](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/)
* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)


