---
title: "Κλάση TiffDataType"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.FileFormats.Tiff.TiffDataType. Ο τύπος δεδομένων tiff"
type: docs
weight: 4680
url: /el/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
{{< psd/tize >}}
## TiffDataType class

Ο τύπος δεδομένων tiff.

```csharp
public abstract class TiffDataType : IComparable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Λαμβάνει το πρόσθετο μέγεθος δεδομένων σε bytes (σε περίπτωση που τα 12 bytes δεν είναι αρκετά για να χωρέσουν τα δεδομένα της ετικέτας). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Λαμβάνει τον αριθμό των στοιχείων. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Λαμβάνει το πρόσθετο μέγεθος δεδομένων σε bytes (σε περίπτωση που τα 12 bytes δεν είναι αρκετά για να χωρέσουν τα δεδομένα της ετικέτας). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Λαμβάνει την ακέραια αναπαράσταση του αναγνωριστικού ετικέτας. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει αν τα δεδομένα της ετικέτας είναι έγκυρα. Η έγκυρη ετικέτα περιέχει δεδομένα που μπορούν να διατηρηθούν. Η μη έγκυρη ετικέτα δεν μπορεί να αποθηκευτεί. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Λαμβάνει το αναγνωριστικό της ετικέτας. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Λαμβάνει τον τύπο της ετικέτας. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Λαμβάνει ή ορίζει την τιμή που περιέχει αυτός ο τύπος δεδομένων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Αναγνώνει τα δεδομένα της ετικέτας. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Συγκρίνει την τρέχουσα περίπτωση με ένα άλλο αντικείμενο του ίδιου τύπου και επιστρέφει έναν ακέραιο που υποδεικνύει αν η τρέχουσα περίπτωση προηγείται, ακολουθεί ή βρίσκεται στην ίδια θέση στη σειρά ταξινόμησης με το άλλο αντικείμενο. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Εκτελεί ένα βαθύ κλώνο αυτής της περίπτωσης. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την περίπτωση. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Γράφει τα πρόσθετα δεδομένα ετικέτας. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Γράφει τα δεδομένα ετικέτας. |

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../)


