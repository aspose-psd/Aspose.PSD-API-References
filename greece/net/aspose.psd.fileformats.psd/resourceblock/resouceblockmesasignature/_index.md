---
title: "ResourceBlock.ResouceBlockMeSaSignature"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Πεδίο ResourceBlock. Η υπογραφή του πόρου του ImageReady"
type: docs
weight: 90
url: /el/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

Η υπογραφή πόρου του ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

## Παραδείγματα

Το παρακάτω παράδειγμα κώδικα δείχνει τη δυνατότητα σωστής φόρτωσης και αποθήκευσης αρχείων PSD με πόρους με υπογραφή MeSa.

```csharp
[C#]

void AreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Values are not equal.");
    }
}

string srcFile = "GST-CHALLAN(2)1..psd";
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
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


