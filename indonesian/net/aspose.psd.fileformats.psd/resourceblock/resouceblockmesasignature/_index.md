---
title: ResourceBlock.ResouceBlockMeSaSignature
second_title: Aspose.PSD untuk Referensi .NET API
description: ResourceBlock bidang. Tanda sumber daya dari ImageReady.
type: docs
weight: 90
url: /id/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
## ResourceBlock.ResouceBlockMeSaSignature field

Tanda sumber daya dari ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

### Contoh

Contoh kode berikutnya menunjukkan kemampuan untuk memuat dengan benar dan menyimpan file PSD dengan sumber daya dengan tanda tangan MeSa.

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

### Lihat juga

* class [ResourceBlock](../)
* ruang nama [Aspose.PSD.FileFormats.Psd](../../resourceblock/)
* perakitan [Aspose.PSD](../../../)


