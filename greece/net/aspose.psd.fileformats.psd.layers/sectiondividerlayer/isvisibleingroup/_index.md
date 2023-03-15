---
title: SectionDividerLayer.IsVisibleInGroup
second_title: Aspose.PSD για Αναφορά API .NET
description: SectionDividerLayer ιδιοκτησία. Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή σε ομάδα Εάν το στρώμα δεν είναι στην ομάδα σημαίνει ομάδα ρίζας.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
## SectionDividerLayer.IsVisibleInGroup property

Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή σε ομάδα (Εάν το στρώμα δεν είναι στην ομάδα, σημαίνει ομάδα ρίζας).

```csharp
public override bool IsVisibleInGroup { get; }
```

### Αξία περιουσίας

`αληθής` εάν αυτή η περίπτωση είναι ορατή στην ομάδα. σε διαφορετική περίπτωση,`ψευδής` .

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει τα επίπεδα SectionDividerLayer και τον τρόπο λήψης του LayerGroup που σχετίζονται με αυτό.

```csharp
[C#]

// Ο παρακάτω κώδικας δείχνει τα επίπεδα SectionDividerLayer και τον τρόπο λήψης του LayerGroup που σχετίζονται με αυτό.

// Ιεραρχία επιπέδων
// [0]: '</Ομάδα επιπέδων>' SectionDividerLayer για Ομάδα 1
// [1]: Κανονικό επίπεδο 'Layer 1'
// [2]: '</Ομάδα επιπέδων>' SectionDividerLayer για Ομάδα 2
// [3]: '</Ομάδα επιπέδων>' SectionDividerLayer για Ομάδα 3
// [4]: «Group 3» GroupLayer
// [5]: «Group 2» GroupLayer
// [6]: «Group 1» GroupLayer

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
    // Προσθήκη κανονικού επιπέδου
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

    // χρησιμοποιώντας τη μέθοδο SectionDividerLayer.GetRelatedLayerGroup(), λαμβάνει τη σχετική παρουσία LayerGroup.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // το ίδιο LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // το ίδιο LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // το ίδιο LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // Η 'Ομάδα 1' περιέχει 5 επίπεδα
}
```

### Δείτε επίσης

* class [SectionDividerLayer](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../sectiondividerlayer/)
* συνέλευση [Aspose.PSD](../../../)


