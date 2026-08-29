---
title: "ShmdResource.SubResources"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα ShmdResource. Λαμβάνει τους υποπόρους του πόρου shmd"
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/subresources/
---
{{< psd/tize >}}
## ShmdResource.SubResources property

Λαμβάνει τους υποπόρους του πόρου shmd.

```csharp
public LayerResource[] SubResources { get; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του πόρου MlstResource που παρέχει έναν χαμηλού επιπέδου μηχανισμό για τη διαχείριση των καταστάσεων του στρώματος.

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

    // Απενεργοποίηση του στρώματος 1 στο πλαίσιο 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Δείτε επίσης

* class [LayerResource](../../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [ShmdResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


