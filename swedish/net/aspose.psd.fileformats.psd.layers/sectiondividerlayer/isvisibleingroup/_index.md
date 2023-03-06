---
title: SectionDividerLayer.IsVisibleInGroup
second_title: Aspose.PSD för .NET API-referens
description: SectionDividerLayer fast egendom. Får ett värde som indikerar om denna instans är synlig i gruppen om lagret inte är i gruppen betyder det rotgrupp.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
## SectionDividerLayer.IsVisibleInGroup property

Får ett värde som indikerar om denna instans är synlig i gruppen (om lagret inte är i gruppen betyder det rotgrupp).

```csharp
public override bool IsVisibleInGroup { get; }
```

### Fastighetsvärde

`Sann` om denna instans är synlig i grupp; annat,`falsk` .

### Exempel

Följande kod visar SectionDividerLayer-lager och hur man får den relaterade LayerGroup.

```csharp
[C#]

// Följande kod visar SectionDividerLayer-lager och hur man får den relaterade LayerGroup till den.

// Lagerhierarki
// [0]: '</Layer group>' SectionDividerLayer för grupp 1
// [1]: 'Layer 1' Vanligt lager
// [2]: '</Layer group>' SectionDividerLayer för grupp 2
// [3]: '</Layer group>' SectionDividerLayer för grupp 3
// [4]: 'Grupp 3' GroupLayer
// [5]: 'Grupp 2' GroupLayer
// [6]: 'Grupp 1' GroupLayer

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // Skapa lagerhierarki
    // Lägg till LayerGroup 'Group 1'
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Lägg till vanligt lager
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // Lägg till LayerGroup 'Group 2'
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // Lägg till LayerGroup 'Group 3'
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // Får SectionDividerLayer's
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // med SectionDividerLayer.GetRelatedLayerGroup()-metoden, erhåller den relaterade LayerGroup-instansen.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // samma LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // samma LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // samma LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Grupp 1' innehåller 5 lager
}
```

### Se även

* class [SectionDividerLayer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../sectiondividerlayer/)
* hopsättning [Aspose.PSD](../../../)


