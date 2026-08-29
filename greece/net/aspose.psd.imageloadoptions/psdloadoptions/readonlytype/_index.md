---
title: "PsdLoadOptions.ReadOnlyType"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα PsdLoadOptions. Λαμβάνει ή ορίζει τη λειτουργία μόνο για ανάγνωση που χρησιμοποιείται κατά τη φόρτωση μιας εικόνας PSD"
type: docs
weight: 80
url: /el/net/aspose.psd.imageloadoptions/psdloadoptions/readonlytype/
---
{{< psd/tize >}}
## PsdLoadOptions.ReadOnlyType property

Λαμβάνει ή ορίζει τη λειτουργία μόνο για ανάγνωση που χρησιμοποιείται κατά τη φόρτωση μιας εικόνας PSD.

```csharp
public ReadOnlyMode ReadOnlyType { get; set; }
```

### Property Value

Μία από τις τιμές του [`ReadOnlyMode`](../readonlymode/):

* !:ReadOnlyMode.None – No restrictions. Image content can be modified.
* !:ReadOnlyMode.Default – The image is fully read-only.
* !:ReadOnlyMode.MetadataEdit – Only metadata can be edited (such as [`ImageResources`](../../../aspose.psd.fileformats.psd/psdimage/imageresources/)), while image pixel content remains read-only.

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

* enum [ReadOnlyMode](../../readonlymode/)
* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


