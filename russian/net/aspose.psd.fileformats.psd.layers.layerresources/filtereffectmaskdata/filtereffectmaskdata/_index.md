---
title: "FilterEffectMaskData.FilterEffectMaskData"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор FilterEffectMaskData. Инициализирует новый экземпляр класса FilterEffectMaskData"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData constructor

Инициализирует новый экземпляр класса [`FilterEffectMaskData`](../).

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| guid | String | guid ресурса. |
| прямоугольник | Rectangle | Прямоугольник каналов. |
| pixelsDepth | Int32 | Глубина пикселей. |
| maxChannels | Int32 | Значение максимального количества каналов. |
| channels | ChannelInformation[] | Каналы. |
| userMask | ChannelInformation | Маска пользователя. |
| maskRectangle | Rectangle | Прямоугольник маски листа. |
| sheetMask | ChannelInformation | Маска листа. |

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

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


