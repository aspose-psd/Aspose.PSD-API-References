---
title: "Класс FilterEffectMaskData"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FilterEffectMaskData класс. Класс данных маски фильтра."
type: docs
weight: 2740
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData class

Класс данных фильтровой маски.

```csharp
public sealed class FilterEffectMaskData
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FilterEffectMaskData](filtereffectmaskdata/)(string, Rectangle, int, int, ChannelInformation[], ChannelInformation, Rectangle, ChannelInformation) | Инициализирует новый экземпляр класса `FilterEffectMaskData`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Channels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/channels/) { get; } | Получает каналы. |
| [GUID](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/guid/) { get; } | Получает GUID. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/length/) { get; } | Получает длину данных маски фильтра в байтах. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maskrectangle/) { get; } | Получает прямоугольник маски листа. |
| [MaxChannels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maxchannels/) { get; } | Получает максимальное количество каналов. |
| [PixelsDepth](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/pixelsdepth/) { get; } | Получает глубину пикселей. |
| [Rectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/rectangle/) { get; } | Получает прямоугольник каналов. |
| [SheetMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/sheetmask/) { get; } | Получает маску листа. |
| [UserMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/usermask/) { get; } | Получает пользовательскую маску. |

## Методы

| Имя | Описание |
| --- | --- |
| [SaveData](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/savedata/)(StreamContainer) | Сохраняет ресурс в указанный контейнер потока. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


