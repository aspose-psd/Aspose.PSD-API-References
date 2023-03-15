---
title: VstkResource.StrokeStyleLineAlignment
second_title: Справочник по Aspose.PSD для .NET API
description: VstkResource свойство. Получает или задает выравнивание линии стиля обводки.
type: docs
weight: 100
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
## VstkResource.StrokeStyleLineAlignment property

Получает или задает выравнивание линии стиля обводки.

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
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

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../vstkresource/)
* сборка [Aspose.PSD](../../../)


