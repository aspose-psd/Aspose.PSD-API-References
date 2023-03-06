---
title: ResourceBlock.ResouceBlockMeSaSignature
second_title: Aspose.PSD for .NET API Referansı
description: ResourceBlock alan. ImageReady. kaynak imzası
type: docs
weight: 90
url: /tr/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
## ResourceBlock.ResouceBlockMeSaSignature field

ImageReady. kaynak imzası

```csharp
public const int ResouceBlockMeSaSignature;
```

### Örnekler

Bir sonraki kod örneği, MeSa imzalı kaynaklarla PSD dosyalarının yüklenmesini düzeltme ve kaydetme becerisini gösterir.

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

### Ayrıca bakınız

* class [ResourceBlock](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../resourceblock/)
* toplantı [Aspose.PSD](../../../)


