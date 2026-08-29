---
title: "Απαρίθμηση ReadOnlyMode"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.ImageLoadOptions.ReadOnlyMode απαρίθμηση. Καθορίζει τις λειτουργίες μόνο για ανάγνωση που διατίθενται κατά τη φόρτωση μιας εικόνας PSD"
type: docs
weight: 5260
url: /el/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

Καθορίζει τις λειτουργίες μόνο για ανάγνωση που είναι διαθέσιμες κατά τη φόρτωση μιας εικόνας PSD.

```csharp
public enum ReadOnlyMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| None | `0` | Δεν εφαρμόζονται περιορισμοί μόνο για ανάγνωση. Η εικόνα μπορεί να τροποποιηθεί πλήρως. |
| Default | `1` | Προεπιλεγμένη λειτουργία. Η εικόνα είναι πλήρως μόνο για ανάγνωση και δεν μπορεί να τροποποιηθεί. |
| MetadataEdit | `2` | Επιτρέπει την επεξεργασία των μεταδεδομένων της εικόνας ενώ το περιεχόμενο της εικόνας παραμένει μόνο για ανάγνωση. |

## Παραδείγματα

Δείχνει την επεξεργασία και αποθήκευση των μεταδεδομένων PSD χρησιμοποιώντας το ReadOnlyMode.MetadataEdit.

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // Αλλαγή μεταδεδομένων στο ReadOnlyMode
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // Αποθήκευση των τροποποιημένων μεταδεδομένων στο ReadOnlyMode
    psdImage.Save(outputFile);
}

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(outputFile)) // Sets the of ReadOnlyMode to true
{
    AssertAreEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);
}

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects should be equal, but they don't.");
    }
}

void AssertAreNotEqual(object obj1, object obj2)
{
    if (object.Equals(obj1, obj2))
    {
        throw new Exception("Objects should not be equal, but they are equal.");
    }
}
```

### Δείτε επίσης

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


