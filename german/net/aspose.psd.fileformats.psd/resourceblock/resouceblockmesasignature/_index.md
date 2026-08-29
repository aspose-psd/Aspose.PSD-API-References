---
title: "ResourceBlock.ResouceBlockMeSaSignature"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ResourceBlock-Feld. Die Ressourcensignatur von ImageReady"
type: docs
weight: 90
url: /de/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

Die Ressourcensignatur von ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

## Beispiele

Das nächste Codebeispiel demonstriert die Fähigkeit, PSD-Dateien mit Ressourcen mit MeSa-Signatur korrekt zu laden und zu speichern.

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

### Siehe auch

* class [ResourceBlock](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


