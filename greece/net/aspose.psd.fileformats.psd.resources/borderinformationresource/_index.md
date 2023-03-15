---
title: Class BorderInformationResource
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Resources.BorderInformationResource τάξη. Ο πόρος με πληροφορίες περιγράμματος των ρυθμίσεων εκτύπωσης εικόνας.
type: docs
weight: 3650
url: /el/net/aspose.psd.fileformats.psd.resources/borderinformationresource/
---
## BorderInformationResource class

Ο πόρος με πληροφορίες περιγράμματος των ρυθμίσεων εκτύπωσης εικόνας.

```csharp
public sealed class BorderInformationResource : ResourceBlock
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [BorderInformationResource](borderinformationresource/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/) { get; } | Λαμβάνει το μέγεθος δεδομένων πόρων σε byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/) { get; } | Αποκτά την ελάχιστη απαιτούμενη έκδοση PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα του πόρου. Συμβολοσειρά Pascal, με επένδυση για να κάνει το μέγεθος ίσο (ένα null όνομα αποτελείται από δύο byte του 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Λαμβάνει την υπογραφή του πόρου. Θα πρέπει να είναι πάντα '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Λαμβάνει το μέγεθος του μπλοκ πόρων σε byte συμπεριλαμβανομένων των δεδομένων του. |
| [Unit](../../aspose.psd.fileformats.psd.resources/borderinformationresource/unit/) { get; set; } | Λαμβάνει ή ορίζει τις μονάδες συνόρων. |
| [Width](../../aspose.psd.fileformats.psd.resources/borderinformationresource/width/) { get; set; } | Λαμβάνει ή ορίζει το πλάτος περιγράμματος. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Αποθηκεύει το μπλοκ πόρων στην καθορισμένη ροή. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Επικυρώνει τις τιμές των πόρων. |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει την υποστήριξη του πόρου BorderInformationResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // ενημέρωση BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Δείτε επίσης

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* συνέλευση [Aspose.PSD](../../)


