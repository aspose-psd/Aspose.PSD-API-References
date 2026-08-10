---
title: "Κλάση ResourceBlock"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.FileFormats.Psd.ResourceBlock. Το μπλοκ πόρων"
type: docs
weight: 4070
url: /el/net/aspose.psd.fileformats.psd/resourceblock/
---
{{< psd/tize >}}
## ResourceBlock class

Το μπλοκ πόρων.

```csharp
public abstract class ResourceBlock
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | Λαμβάνει το μέγεθος δεδομένων του πόρου σε byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | Λαμβάνει την ελάχιστη απαιτούμενη έκδοση PSD. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα του πόρου. Συμβολοσειρά Pascal, συμπληρωμένη ώστε το μέγεθος να είναι άρτιο (ένα κενό όνομα αποτελείται από δύο byte του 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Λαμβάνει την υπογραφή του πόρου. Πρέπει πάντα να είναι '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Λαμβάνει το μέγεθος του μπλοκ πόρου σε byte, συμπεριλαμβανομένων των δεδομένων του. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Αποθηκεύει το μπλοκ πόρου στο καθορισμένο ρεύμα. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Επικυρώνει τις τιμές του πόρου. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | Η υπογραφή πόρου του ImageReady. |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | Η κανονική υπογραφή πόρου του Photoshop. |

## Άλλα μέλη

| Όνομα | Περιγραφή |
| --- | --- |
| enum [ResourceBlockState](../../aspose.psd.fileformats.psd/resourceblock.resourceblockstate) | Αντιπροσωπεύει την κατάσταση του μπλοκ πόρων. |

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


