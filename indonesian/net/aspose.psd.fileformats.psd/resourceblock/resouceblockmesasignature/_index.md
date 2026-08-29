---
title: "ResourceBlock.ResouceBlockMeSaSignature"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Field ResourceBlock. Tanda tangan sumber daya dari ImageReady"
type: docs
weight: 90
url: /id/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

Tanda tangan sumber daya ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

## Contoh

Contoh kode berikut menunjukkan kemampuan untuk memuat dan menyimpan file PSD dengan sumber daya yang memiliki tanda tangan MeSa secara tepat.

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

### Lihat Juga

* class [ResourceBlock](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


