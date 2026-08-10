---
title: "SectionDividerLayer.IsVisibleInGroup"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα SectionDividerLayer. Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή στην ομάδα. Εάν το στρώμα δεν είναι σε ομάδα, σημαίνει ότι είναι η ρίζα της ομάδας"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
{{< psd/tize >}}
## SectionDividerLayer.IsVisibleInGroup property

Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή στην ομάδα (Εάν το στρώμα δεν βρίσκεται σε ομάδα, σημαίνει ότι είναι η ριζική ομάδα).

```csharp
public override bool IsVisibleInGroup { get; }
```

### Property Value

`true` εάν αυτή η παρουσία είναι ορατή στην ομάδα· διαφορετικά, `false`.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τις στρώσεις SectionDividerLayer και πώς να λάβετε τη σχετική με αυτές LayerGroup.

```csharp
[C#]

// Ο παρακάτω κώδικας δείχνει τις στρώσεις SectionDividerLayer και πώς να λάβετε τη σχετική με αυτές LayerGroup.

// Ιεραρχία στρώσεων
//    [0]: '</Layer group>' SectionDividerLayer για την Ομάδα 1
//    [1]: 'Layer 1' Κανονική Στρώση
//    [2]: '</Layer group>' SectionDividerLayer για την Ομάδα 2
//    [3]: '</Layer group>' SectionDividerLayer για την Ομάδα 3
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
    // Δημιουργία ιεραρχίας επιπέδων
    // Προσθέστε το LayerGroup 'Group 1'
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Προσθέστε κανονικό επίπεδο
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // Προσθέστε το LayerGroup 'Group 2'
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // Προσθέστε το LayerGroup 'Group 3'
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // Λαμβάνει το SectionDividerLayer's
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // χρησιμοποιώντας τη μέθοδο SectionDividerLayer.GetRelatedLayerGroup(), λαμβάνει το σχετικό αντικείμενο LayerGroup.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // the same LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' contains 5 layers
}
```

### Δείτε επίσης

* class [SectionDividerLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


