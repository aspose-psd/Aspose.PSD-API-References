---
title: Enum LineCapType
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineCapType перечисление. Тип заглавной строки.
type: docs
weight: 3040
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype/
---
## LineCapType enumeration

Тип заглавной строки.

```csharp
public enum LineCapType : short
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| RoundCap | `0` | Тип круглой крышки. |
| SquareCap | `1` | Тип квадратной крышки. |
| ButtCap | `2` | Тип приклада. |

### Примеры

Следующий код демонстрирует поддержку ресурса VstkResource.

```csharp
[C#]

string srcFile = "StrokeShapeTest1.psd";
string dstFile = "StrokeShapeTest2.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    Layer layer = image.Layers[1];
    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is VstkResource)
        {
            VstkResource vstkResource = (VstkResource)resource;
            vstkResource.StrokeStyleLineAlignment = StrokePosition.Outside;
            vstkResource.StrokeStyleLineWidth = 20;
        }
    }

    image.Save(dstFile);
}
```

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* сборка [Aspose.PSD](../../)


