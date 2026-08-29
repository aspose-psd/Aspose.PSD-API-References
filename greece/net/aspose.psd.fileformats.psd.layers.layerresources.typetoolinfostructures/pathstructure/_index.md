---
title: "Κλάση PathStructure"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.PathStructure class. Η δομή διαδρομής"
type: docs
weight: 3610
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/
---
{{< psd/tize >}}
## PathStructure class

Η δομή path.

```csharp
public sealed class PathStructure : OSTypeStructure
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PathStructure](pathstructure/)(ClassID) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PathStructure`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/) { get; } | Λαμβάνει το κλειδί της δομής. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Λαμβάνει ή ορίζει το όνομα του κλειδιού. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/) { get; } | Λαμβάνει το μήκος του [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) σε bytes. |
| [Path](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/) { get; set; } | Λαμβάνει ή ορίζει τη διαδρομή. |
| [Prefix](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/) { get; set; } | Λαμβάνει ή ορίζει το πρόθεμα της διαδρομής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Λαμβάνει το μήκος της κεφαλίδας. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Αποθηκεύει τη δομή στο καθορισμένο κοντέινερ ροής. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Αποθηκεύει τη δομή στο καθορισμένο κοντέινερ ροής. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/) | Αναγνωρίζει το κλειδί της δομής. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα φόρτωσης αρχείου με τη δομή PathStructure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Δείτε επίσης

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


