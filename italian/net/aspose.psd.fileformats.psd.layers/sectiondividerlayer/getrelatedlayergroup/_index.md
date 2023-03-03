---
title: SectionDividerLayer.GetRelatedLayerGroup
second_title: Aspose.PSD per riferimento API .NET
description: SectionDividerLayer metodo. Ottiene ilLayerGroup è legato a questoSectionDividerLayer istanza.
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/getrelatedlayergroup/
---
## SectionDividerLayer.GetRelatedLayerGroup method

Ottiene il[`LayerGroup`](../../layergroup/) è legato a questo[`SectionDividerLayer`](../) istanza.

```csharp
public LayerGroup GetRelatedLayerGroup()
```

### Valore di ritorno

IL[`LayerGroup`](../../layergroup/) esempio.

### Esempi

Il codice seguente illustra i layer SectionDividerLayer e come ottenere il relativo LayerGroup.

```csharp
[C#]

// Il codice seguente mostra i layer SectionDividerLayer e come ottenere il relativo LayerGroup.

// Gerarchia dei livelli
// [0]: '</Gruppo livelli>' SectionDividerLayer per il gruppo 1
// [1]: 'Livello 1' Livello regolare
// [2]: '</Gruppo livelli>' SectionDividerLayer per il gruppo 2
// [3]: '</Gruppo livelli>' SectionDividerLayer per il gruppo 3
// [4]: 'Gruppo 3' GroupLayer
// [5]: 'Gruppo 2' GroupLayer
// [6]: 'Gruppo 1' GroupLayer

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // Creazione della gerarchia dei livelli
    // Aggiungi il LayerGroup 'Gruppo 1'
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Aggiungi un livello regolare
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // Aggiungi il LayerGroup 'Gruppo 2'
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // Aggiungi il LayerGroup 'Gruppo 3'
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // Ottiene il SectionDividerLayer
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // utilizzando il metodo SectionDividerLayer.GetRelatedLayerGroup(), ottiene l'istanza LayerGroup correlata.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // lo stesso LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // lo stesso LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // lo stesso LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Gruppo 1' contiene 5 livelli
}
```

### Guarda anche

* class [LayerGroup](../../layergroup/)
* class [SectionDividerLayer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../sectiondividerlayer/)
* assemblea [Aspose.PSD](../../../)


