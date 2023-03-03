---
title: MlstResource.Items
second_title: Aspose.PSD για Αναφορά API .NET
description: MlstResource ιδιοκτησία. Λαμβάνει ή ορίζει τις δομές.
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
## MlstResource.Items property

Λαμβάνει ή ορίζει τις δομές.

```csharp
public OSTypeStructure[] Items { get; }
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

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../mlstresource/)
* συνέλευση [Aspose.PSD](../../../)


