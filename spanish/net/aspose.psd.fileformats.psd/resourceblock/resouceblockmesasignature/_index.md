---
title: "ResourceBlock.ResouceBlockMeSaSignature"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Campo ResourceBlock. La firma del recurso de ImageReady"
type: docs
weight: 90
url: /es/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

La firma de recurso de ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

## Ejemplos

El siguiente ejemplo de código demuestra la capacidad de cargar y guardar correctamente archivos PSD con recursos con firma MeSa.

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

### Ver también

* class [ResourceBlock](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


