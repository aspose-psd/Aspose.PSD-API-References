---
title: "FilterEffectMaskData.GUID"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство FilterEffectMaskData. Возвращает GUID"
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/guid/
---
{{< psd/tize >}}
## FilterEffectMaskData.GUID property

Получает GUID.

```csharp
public string GUID { get; }
```

## Примеры

Этот пример демонстрирует, как получать и задавать свойства ресурса FXidResource.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
long maskLength = 369;

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

using (var psdImage = (PsdImage)Image.Load(inputFilePath))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }

    psdImage.Save(output);
}

// проверьте после сохранения
using (var psdImage = (PsdImage)Image.Load(output))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }
}
```

### См. также

* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


