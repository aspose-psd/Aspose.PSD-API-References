---
title: ResourceBlock.ResouceBlockMeSaSignature
second_title: Aspose.PSD voor .NET API-referentie
description: ResourceBlock veld. De bronhandtekening van ImageReady.
type: docs
weight: 90
url: /nl/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
## ResourceBlock.ResouceBlockMeSaSignature field

De bronhandtekening van ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

### Voorbeelden

Het volgende codevoorbeeld demonstreert de mogelijkheid om PSD-bestanden correct te laden en op te slaan met bronnen met MeSa-handtekening.

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

### Zie ook

* class [ResourceBlock](../)
* naamruimte [Aspose.PSD.FileFormats.Psd](../../resourceblock/)
* montage [Aspose.PSD](../../../)


