---
title: VstkResource.StrokeStyleLineWidth
second_title: Справочник по Aspose.PSD для .NET API
description: VstkResource свойство. Получает или задает ширину линии обводки.
type: docs
weight: 160
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/
---
## VstkResource.StrokeStyleLineWidth property

Получает или задает ширину линии обводки.

```csharp
public double StrokeStyleLineWidth { get; set; }
```

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

* class [VstkResource](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* сборка [Aspose.PSD](../../../)


