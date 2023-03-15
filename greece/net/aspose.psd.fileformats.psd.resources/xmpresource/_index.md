---
title: Class XmpResource
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Resources.XmpResource τάξη. Αντιπροσωπεύει τον πόρο μεταδεδομένων XMP.
type: docs
weight: 3990
url: /el/net/aspose.psd.fileformats.psd.resources/xmpresource/
---
## XmpResource class

Αντιπροσωπεύει τον πόρο μεταδεδομένων XMP.

```csharp
public sealed class XmpResource : ResourceBlock
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [XmpResource](xmpresource/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/xmpresource/datasize/) { get; } | Λαμβάνει το μέγεθος δεδομένων πόρων σε byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό για τον πόρο. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/xmpresource/minimalversion/) { get; } | Λαμβάνει την ελάχιστη απαιτούμενη έκδοση psd. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα του πόρου. Συμβολοσειρά Pascal, με επένδυση για να κάνει το μέγεθος ίσο (ένα null όνομα αποτελείται από δύο byte του 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Λαμβάνει την υπογραφή του πόρου. Θα πρέπει να είναι πάντα '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Λαμβάνει το μέγεθος του μπλοκ πόρων σε byte συμπεριλαμβανομένων των δεδομένων του. |
| [XmpData](../../aspose.psd.fileformats.psd.resources/xmpresource/xmpdata/) { get; set; } | Λήψη ή ρύθμιση XMP data container |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Αποθηκεύει το μπλοκ πόρων στην καθορισμένη ροή. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Επικυρώνει τις τιμές των πόρων. |

### Δείτε επίσης

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* συνέλευση [Aspose.PSD](../../)


