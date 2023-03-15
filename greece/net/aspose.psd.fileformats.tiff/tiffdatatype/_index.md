---
title: Class TiffDataType
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Tiff.TiffDataType τάξη. Ο τύπος δεδομένων tiff.
type: docs
weight: 4210
url: /el/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

Ο τύπος δεδομένων tiff.

```csharp
public abstract class TiffDataType : IComparable
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Λαμβάνει το πρόσθετο μέγεθος δεδομένων σε byte (σε περίπτωση που τα 12 byte δεν είναι αρκετά για να χωρέσουν τα δεδομένα της ετικέτας). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Λαμβάνει τον αριθμό των στοιχείων. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Λαμβάνει το πρόσθετο μέγεθος δεδομένων σε byte (σε περίπτωση που τα 12 byte δεν είναι αρκετά για να χωρέσουν τα δεδομένα της ετικέτας). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Λαμβάνει αναπαράσταση ακέραιου αριθμού αναγνωριστικού ετικέτας. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα ετικέτας είναι έγκυρα. Η έγκυρη ετικέτα περιέχει δεδομένα που μπορούν να διατηρηθούν. Δεν είναι δυνατή η αποθήκευση της μη έγκυρης ετικέτας. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Λαμβάνει το αναγνωριστικό ετικέτας. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Λαμβάνει τον τύπο ετικέτας. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Λαμβάνει ή ορίζει την τιμή που περιέχει αυτός ο τύπος δεδομένων. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Διαβάζει τα δεδομένα της ετικέτας. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Συγκρίνει την τρέχουσα παρουσία με ένα άλλο αντικείμενο του ίδιου τύπου και επιστρέφει έναν ακέραιο που υποδεικνύει εάν η τρέχουσα παρουσία προηγείται, ακολουθεί ή εμφανίζεται στην ίδια θέση με τη σειρά ταξινόμησης με το άλλο αντικείμενο. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Εκτελεί έναν βαθύ κλώνο αυτής της παρουσίας. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Επιστρέφει αString που αντιπροσωπεύει αυτήν την περίπτωση. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Γράφει τα πρόσθετα δεδομένα ετικέτας. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Γράφει τα δεδομένα της ετικέτας. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* συνέλευση [Aspose.PSD](../../)


