---
title: "ResourceBlock.ResouceBlockMeSaSignature"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ResourceBlock alanı. ImageReady'ın kaynak imzası"
type: docs
weight: 90
url: /tr/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

ImageReady'ın kaynak imzası.

```csharp
public const int ResouceBlockMeSaSignature;
```

## Örnekler

Aşağıdaki kod örneği, MeSa imzasına sahip kaynaklarla PSD dosyalarını doğru şekilde yükleme ve kaydetme yeteneğini gösterir.

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

### Ayrıca Bakınız

* class [ResourceBlock](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


