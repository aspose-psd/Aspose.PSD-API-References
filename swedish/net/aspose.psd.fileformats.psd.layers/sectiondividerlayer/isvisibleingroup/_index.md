---
title: "SectionDividerLayer.IsVisibleInGroup"
second_title: "Aspose.PSD för .NET API‑referens"
description: "SectionDividerLayer-egenskap. Hämtar ett värde som indikerar om detta objekt är synligt i grupp. Om lagret inte är i en grupp betyder det rotgrupp"
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
{{< psd/tize >}}
## SectionDividerLayer.IsVisibleInGroup property

Hämtar ett värde som indikerar om detta objekt är synligt i grupp(Om lagret inte är i en grupp betyder det rotgrupp).

```csharp
public override bool IsVisibleInGroup { get; }
```

### Property Value

`true` om denna instans är synlig i grupp; annars, `false`.

## Exempel

Följande kod demonstrerar SectionDividerLayer-lager och hur man hämtar det relaterade LayerGroup.

```csharp
[C#]

// Följande kod demonstrerar SectionDividerLayer-lager och hur man hämtar det relaterade LayerGroup.

// Lagerhierarki
//    [0]: '</Layer group>' SectionDividerLayer för Grupp 1
//    [1]: 'Layer 1' Vanligt lager
//    [2]: '</Layer group>' SectionDividerLayer för Grupp 2
//    [3]: '</Layer group>' SectionDividerLayer för Grupp 3
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

    // Hämtar SectionDividerLayer:s
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // med metoden SectionDividerLayer.GetRelatedLayerGroup() får man den relaterade LayerGroup-instansen.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // the same LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' contains 5 layers
}
```

### Se även

* class [SectionDividerLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


