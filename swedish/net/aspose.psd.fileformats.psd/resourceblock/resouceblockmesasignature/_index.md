---
title: "ResourceBlock.ResouceBlockMeSaSignature"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ResourceBlock-fält. Resurssignaturen för ImageReady"
type: docs
weight: 90
url: /sv/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

Resurssignaturen för ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

## Exempel

Det följande kodexemplet demonstrerar förmågan att korrekt läsa in och spara PSD-filer med resurser med MeSa-signatur.

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

### Se även

* class [ResourceBlock](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


