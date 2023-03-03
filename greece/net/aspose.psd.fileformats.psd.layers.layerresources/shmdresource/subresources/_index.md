---
title: ShmdResource.SubResources
second_title: Aspose.PSD για Αναφορά API .NET
description: ShmdResource ιδιοκτησία. Λαμβάνει τους δευτερεύοντες πόρους του πόρου shmd.
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
## ShmdResource.SubResources property

Λαμβάνει τους δευτερεύοντες πόρους του πόρου shmd.

```csharp
public LayerResource[] SubResources { get; }
```

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του πόρου MlstResource που παρέχει έναν μηχανισμό χαμηλού επιπέδου για τον χειρισμό των καταστάσεων του επιπέδου.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // Απενεργοποιήστε το επίπεδο 1 στο πλαίσιο 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Δείτε επίσης

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../shmdresource/)
* συνέλευση [Aspose.PSD](../../../)


