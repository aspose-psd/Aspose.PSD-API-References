---
title: SectionDividerLayer.IsVisibleInGroup
second_title: Référence de l'API Aspose.PSD pour .NET
description: SectionDividerLayer propriété. Obtient une valeur indiquant si cette instance est visible dans le groupe si la couche nest pas dans le groupe cela signifie le groupe racine.
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
## SectionDividerLayer.IsVisibleInGroup property

Obtient une valeur indiquant si cette instance est visible dans le groupe (si la couche n'est pas dans le groupe, cela signifie le groupe racine).

```csharp
public override bool IsVisibleInGroup { get; }
```

### Valeur de la propriété

`vrai` si cette instance est visible dans le groupe ; sinon,`FAUX` .

### Exemples

Le code suivant illustre les couches SectionDividerLayer et comment obtenir le LayerGroup associé.

```csharp
[C#]

// Le code suivant illustre les couches SectionDividerLayer et comment obtenir le LayerGroup associé.

// Hiérarchie des calques
// [0] : '</Groupe de calques>' SectionDividerLayer pour le groupe 1
// [1] : 'Calque 1' Couche régulière
// [2] : '</Groupe de calques>' SectionDividerLayer pour le groupe 2
// [3] : '</Groupe de calques>' SectionDividerLayer pour le groupe 3
// [4] : 'Groupe 3' GroupLayer
// [5] : couche de groupe 'Groupe 2'
// [6] : 'Groupe 1' GroupLayer

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
    // Ajouter le LayerGroup 'Groupe 1'
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Ajout d'un calque normal
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // Ajouter le LayerGroup 'Groupe 2'
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // Ajouter le LayerGroup 'Groupe 3'
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // Obtient le SectionDividerLayer
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // à l'aide de la méthode SectionDividerLayer.GetRelatedLayerGroup(), obtient l'instance LayerGroup associée.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // le même LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // le même LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // le même LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Groupe 1' contient 5 calques
}
```

### Voir également

* class [SectionDividerLayer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../sectiondividerlayer/)
* Assemblée [Aspose.PSD](../../../)


