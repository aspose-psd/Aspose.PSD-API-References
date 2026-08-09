---
title: "SectionDividerLayer.IsVisibleInGroup"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "SectionDividerLayer-Eigenschaft. Gibt einen Wert zurück, der angibt, ob diese Instanz in der Gruppe sichtbar ist. Wenn die Ebene nicht in einer Gruppe ist, bedeutet dies die Root-Gruppe"
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
{{< psd/tize >}}
## SectionDividerLayer.IsVisibleInGroup property

Liefert einen Wert, der angibt, ob diese Instanz in einer Gruppe sichtbar ist (Wenn die Ebene nicht in einer Gruppe ist, bedeutet das die Stammgruppe).

```csharp
public override bool IsVisibleInGroup { get; }
```

### Property Value

`true`, wenn diese Instanz in einer Gruppe sichtbar ist; andernfalls `false`.

## Beispiele

Der folgende Code demonstriert SectionDividerLayer‑Ebenen und zeigt, wie man die zugehörige LayerGroup erhält.

```csharp
[C#]

// Der folgende Code demonstriert SectionDividerLayer‑Ebenen und zeigt, wie man die zugehörige LayerGroup erhält.

// Ebenenhierarchie
//    [0]: '</Layer group>' SectionDividerLayer für Gruppe 1
//    [1]: 'Layer 1' Normale Ebene
//    [2]: '</Layer group>' SectionDividerLayer für Gruppe 2
//    [3]: '</Layer group>' SectionDividerLayer für Gruppe 3
//    [4]: 'Group 3' Gruppenebene
//    [5]: 'Group 2' Gruppenebene
//    [6]: 'Group 1' Gruppenebene

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // Erstellen der Ebenenhierarchie
    // Füge die LayerGroup 'Group 1' hinzu
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Füge eine reguläre Ebene hinzu
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // Füge die LayerGroup 'Group 2' hinzu
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // Füge die LayerGroup 'Group 3' hinzu
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // Ermittelt die SectionDividerLayer‑
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // Verwendet die Methode SectionDividerLayer.GetRelatedLayerGroup(), um die zugehörige LayerGroup‑Instanz zu erhalten.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // the same LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' contains 5 layers
}
```

### Siehe auch

* class [SectionDividerLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


