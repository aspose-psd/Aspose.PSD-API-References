---
title: Class MlstResource
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource τάξη. Ο πόρος mlst. Αυτή η κλάση μεταξύ άλλων περιέχει πληροφορίες σχετικά με τη θέση του επιπέδου στη γραμμή χρόνου.
type: docs
weight: 2830
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
## MlstResource class

Ο πόρος mlst. Αυτή η κλάση, μεταξύ άλλων, περιέχει πληροφορίες σχετικά με τη θέση του επιπέδου στη γραμμή χρόνου.

```csharp
public class MlstResource : LayerResource
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [MlstResource](mlstresource/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | Λαμβάνει ή ορίζει την έκδοση περιγραφής. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | Λαμβάνει ή ορίζει τις δομές. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/key/) { get; } | Λαμβάνει το κλειδί πόρων επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/psdversion/) { get; } | Λαμβάνει την έκδοση psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/signature/) { get; } | Παίρνει την υπογραφή. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | Αποθηκεύει το καθορισμένο κοντέινερ ροής. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει αString που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | Το κλειδί πληροφοριών εργαλείου τύπου. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* συνέλευση [Aspose.PSD](../../)


