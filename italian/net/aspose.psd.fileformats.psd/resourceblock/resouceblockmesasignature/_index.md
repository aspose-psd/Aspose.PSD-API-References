---
title: ResouceBlockMeSaSignature
second_title: Riferimento all'API di Aspose.PSD per .NET
description: La firma della risorsa di ImageReady.
type: docs
weight: 90
url: /it/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
## ResourceBlock.ResouceBlockMeSaSignature field

La firma della risorsa di ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

### Esempi

L'esempio di codice successivo mostra la capacità di correggere il caricamento e salvare i file PSD con risorse con firma MeSa.

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

### Guarda anche

* class [ResourceBlock](../../resourceblock)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../resourceblock)
* assemblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->