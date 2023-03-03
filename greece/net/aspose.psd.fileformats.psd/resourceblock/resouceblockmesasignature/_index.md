---
title: ResourceBlock.ResouceBlockMeSaSignature
second_title: Aspose.PSD για Αναφορά API .NET
description: ResourceBlock πεδίο. Η υπογραφή πόρων του ImageReady.
type: docs
weight: 90
url: /el/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
## ResourceBlock.ResouceBlockMeSaSignature field

Η υπογραφή πόρων του ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

### Παραδείγματα

Το επόμενο παράδειγμα κώδικα δείχνει την ικανότητα διόρθωσης φόρτωσης και αποθήκευσης αρχείων PSD με πόρους με υπογραφή MeSa.

```csharp
[C#]

void AreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Values are not equal.");
    }
}

string srcFile = "GST-CHALLAN(21..psd");
string output = "output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[23].Signature);
    AreEqual(ResourceBlock.ResouceBlockMeSaSignature, psdImage.ImageResources[24].Signature);
    psdImage.Save(output);
}
```

### Δείτε επίσης

* class [ResourceBlock](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd](../../resourceblock/)
* συνέλευση [Aspose.PSD](../../../)


