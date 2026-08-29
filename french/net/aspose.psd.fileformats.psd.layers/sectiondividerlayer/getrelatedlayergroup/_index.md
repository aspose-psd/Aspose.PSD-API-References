---
title: "SectionDividerLayer.GetRelatedLayerGroup"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode SectionDividerLayer. Obtient le LayerGroup qui est lié à cette instance de SectionDividerLayer"
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/getrelatedlayergroup/
---
{{< psd/tize >}}
## SectionDividerLayer.GetRelatedLayerGroup method

Obtient le [`LayerGroup`](../../layergroup/) qui est lié à cette instance de [`SectionDividerLayer`](../).

```csharp
public LayerGroup GetRelatedLayerGroup()
```

### Valeur de retour

L'instance du [`LayerGroup`](../../layergroup/).

## Exemples

Le code suivant montre les calques SectionDividerLayer et comment obtenir le LayerGroup qui leur est lié.

```csharp
[C#]

// Le code suivant montre les calques SectionDividerLayer et comment obtenir le LayerGroup qui leur est lié.

// Hiérarchie des calques
//    [0]: '</Layer group>' SectionDividerLayer pour le groupe 1
//    [1]: 'Layer 1' Calque régulier
//    [2]: '</Layer group>' SectionDividerLayer pour le groupe 2
//    [3]: '</Layer group>' SectionDividerLayer pour le groupe 3
//    [4]: 'Group 3' GroupLayer
//    [5]: 'Group 2' GroupLayer
//    [6]: 'Group 1' GroupLayer

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // Création de la hiérarchie des calques
    // Ajouter le LayerGroup 'Group 1'
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Ajouter un calque ordinaire
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // Ajouter le LayerGroup 'Group 2'
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // Ajouter le LayerGroup 'Group 3'
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // Obtient le SectionDividerLayer
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // en utilisant la méthode SectionDividerLayer.GetRelatedLayerGroup(), obtient l'instance du LayerGroup associé.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // the same LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' contains 5 layers
}
```

### Voir aussi

* class [LayerGroup](../../layergroup/)
* class [SectionDividerLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


