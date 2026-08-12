---
title: "ResourceBlock.ResouceBlockMeSaSignature"
second_title: "Справочник API Aspose.PSD для .NET"
description: "ResourceBlock поле. Подпись ресурса ImageReady"
type: docs
weight: 90
url: /ru/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
{{< psd/tize >}}
## ResourceBlock.ResouceBlockMeSaSignature field

Подпись ресурса ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

## Примеры

Следующий пример кода демонстрирует возможность корректно загружать и сохранять PSD‑файлы с ресурсами, имеющими подпись MeSa.

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

### См. также

* class [ResourceBlock](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


