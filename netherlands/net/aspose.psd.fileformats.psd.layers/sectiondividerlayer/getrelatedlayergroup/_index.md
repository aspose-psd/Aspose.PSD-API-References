---
title: SectionDividerLayer.GetRelatedLayerGroup
second_title: Aspose.PSD voor .NET API-referentie
description: SectionDividerLayer methode. Krijgt deLayerGroup dat heeft hiermee te makenSectionDividerLayer instantie.
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/getrelatedlayergroup/
---
## SectionDividerLayer.GetRelatedLayerGroup method

Krijgt de[`LayerGroup`](../../layergroup/) dat heeft hiermee te maken[`SectionDividerLayer`](../) instantie.

```csharp
public LayerGroup GetRelatedLayerGroup()
```

### Winstwaarde

De[`LayerGroup`](../../layergroup/) voorbeeld.

### Voorbeelden

De volgende code demonstreert SectionDividerLayer-lagen en hoe u de gerelateerde LayerGroup kunt krijgen.

```csharp
[C#]

// De volgende code demonstreert SectionDividerLayer-lagen en hoe de gerelateerde LayerGroup te verkrijgen.

// Lagenhiërarchie
// [0]: '</Lagengroep>' SectionDividerLayer voor Groep 1
// [1]: 'Laag 1' reguliere laag
// [2]: '</Lagengroep>' SectieDividerLayer voor Groep 2
// [3]: '</Lagengroep>' SectieDividerLayer voor groep 3
// [4]: Groepslaag 'Groep 3'
// [5]: Groepslaag 'Groep 2'
// [6]: Groepslaag 'Groep 1'

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // Lagenhiërarchie maken
    // Voeg de LayerGroup 'Groep 1' toe
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Voeg gewone laag toe
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // Voeg de LayerGroup 'Groep 2' toe
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // Voeg de LayerGroup 'Groep 3' toe
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // Haalt de SectionDividerLayer's op
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // met behulp van de methode SectionDividerLayer.GetRelatedLayerGroup() wordt de gerelateerde LayerGroup-instantie verkregen.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // dezelfde LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // dezelfde LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // dezelfde LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Groep 1' bevat 5 lagen
}
```

### Zie ook

* class [LayerGroup](../../layergroup/)
* class [SectionDividerLayer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../sectiondividerlayer/)
* montage [Aspose.PSD](../../../)


