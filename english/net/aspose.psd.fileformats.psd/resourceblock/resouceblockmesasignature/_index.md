---
title: ResourceBlock.ResouceBlockMeSaSignature
second_title: Aspose.PSD for .NET API Reference
description: ResourceBlock field. The resource signature of ImageReady
type: docs
weight: 90
url: /net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

The resource signature of ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

## Examples

The next code example demonstrates ability to correct load and save PSD files with resources with MeSa signature.

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

### See Also

* class [ResourceBlock](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../resourceblock/)
* assembly [Aspose.PSD](../../../)


