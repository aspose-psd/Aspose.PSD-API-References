---
title: "Κλάση NameStructure"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.NameStructure class. Το κλειδί της δομής Name 0x6E616D65, που γράφει name σε ASCII, είναι μια απλή δομή που χρησιμοποιείται για την αποθήκευση μιας συμβολοσειράς Unicode ή Pascalstyle που αντιπροσωπεύει το όνομα ενός στοιχείου όπως μια διαδρομή στρώσης ή προσαρμογή"
type: docs
weight: 3580
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/
---
{{< psd/tize >}}
## NameStructure class

Η δομή Name (κλειδί: 0x6E616D65, που αντιστοιχεί στο "name" σε ASCII) είναι μια απλή δομή που χρησιμοποιείται για την αποθήκευση μιας συμβολοσειράς Unicode ή τύπου Pascal που αντιπροσωπεύει το όνομα ενός στοιχείου, όπως ένα στρώμα, μια διαδρομή ή μια προσαρμογή.

```csharp
public sealed class NameStructure : OSTypeStructure
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [NameStructure](namestructure/)(ClassID) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `NameStructure`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/key/) { get; } | Λαμβάνει το κλειδί. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Λαμβάνει ή ορίζει το όνομα του κλειδιού. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/length/) { get; } | Λαμβάνει το μήκος του [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) σε bytes. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/value/) { get; set; } | Λαμβάνει ή ορίζει την τιμή μιας δομής Name. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Λαμβάνει το μήκος της κεφαλίδας. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Αποθηκεύει τη δομή στο καθορισμένο κοντέινερ ροής. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Αποθηκεύει τη δομή στο καθορισμένο κοντέινερ ροής. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/structurekey/) | Το κλειδί της δομής Name. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του NameStructure.

```csharp
[C#]

string inputFile = "Mixer_ipad_Hand_W_crash.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(inputFile, new PsdLoadOptions { DataRecoveryMode = DataRecoveryMode.MaximalRecover }))
{
    //// Το αρχείο φορτώθηκε επιτυχώς

    SmartObjectLayer layer = (SmartObjectLayer)psdImage.Layers[3];
    SoLdResource resource = (SoLdResource)layer.Resources[9];

    DescriptorStructure struct1 = (DescriptorStructure)resource.Items[15];
    ListStructure struct2 = (ListStructure)struct1.Structures[5];
    DescriptorStructure struct3 = (DescriptorStructure)struct2.Types[0];
    DescriptorStructure struct4 = (DescriptorStructure)struct3.Structures[6];
    ReferenceStructure struct5 = (ReferenceStructure)struct4.Structures[8];
    NameStructure nameStructure = (NameStructure)struct5.Items[0];

    AssertIsNotNull(nameStructure);
    AssertAreEqual(37, nameStructure.Length);
    AssertAreEqual("None\0", nameStructure.Value);

    // Αποθήκευσε το δοκιμαστικό αρχείο χωρίς αλλαγές
    psdImage.Save(outputFile);

    //// Το αρχείο πρέπει να ανοίξει στο PS χωρίς σφάλματα
}

// Έλεγξε ότι οι δομές των εφέ φωτισμού αποθηκεύονται σωστά
using (var psdImage = (PsdImage)Image.Load(
           outputFile,
           new PsdLoadOptions { DataRecoveryMode = DataRecoveryMode.MaximalRecover }))
{
    SmartObjectLayer layer = (SmartObjectLayer)psdImage.Layers[3];
    SoLdResource resource = (SoLdResource)layer.Resources[9];

    DescriptorStructure struct1 = (DescriptorStructure)resource.Items[15];
    ListStructure struct2 = (ListStructure)struct1.Structures[5];
    DescriptorStructure struct3 = (DescriptorStructure)struct2.Types[0];
    DescriptorStructure struct4 = (DescriptorStructure)struct3.Structures[6];
    ReferenceStructure struct5 = (ReferenceStructure)struct4.Structures[8];
    NameStructure nameStructure = (NameStructure)struct5.Items[0];

    AssertIsNotNull(nameStructure);
    AssertAreEqual(37, nameStructure.Length);
    AssertAreEqual("None\0", nameStructure.Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

void AssertIsNotNull(object actual)
{
    if (actual == null)
    {
        throw new Exception("Object is null.");
    }
}
```

### Δείτε επίσης

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


