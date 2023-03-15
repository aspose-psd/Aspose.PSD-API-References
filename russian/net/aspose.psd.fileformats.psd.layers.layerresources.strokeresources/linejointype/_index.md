---
title: Enum LineJoinType
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.LineJoinType перечисление. Тип соединения линий.
type: docs
weight: 3050
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype/
---
## LineJoinType enumeration

Тип соединения линий.

```csharp
public enum LineJoinType : short
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| BevelJoin | `0` | Тип соединения со скосом. |
| RoundJoin | `1` | Тип округления. |
| MiterJoin | `2` | Тип соединения Mitre. |

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


