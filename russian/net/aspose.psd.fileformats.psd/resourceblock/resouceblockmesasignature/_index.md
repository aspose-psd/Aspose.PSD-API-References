---
title: ResourceBlock.ResouceBlockMeSaSignature
second_title: Справочник по Aspose.PSD для .NET API
description: ResourceBlock поле. Подпись ресурса ImageReady.
type: docs
weight: 90
url: /ru/net/aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/
---
## ResourceBlock.ResouceBlockMeSaSignature field

Подпись ресурса ImageReady.

```csharp
public const int ResouceBlockMeSaSignature;
```

### Примеры

Следующий пример кода демонстрирует возможность корректной загрузки и сохранения файлов PSD с ресурсами с подписью MeSa.

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

### Смотрите также

* class [ResourceBlock](../)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../resourceblock/)
* сборка [Aspose.PSD](../../../)


