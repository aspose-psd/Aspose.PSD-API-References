---
title: "VstkResource.StrokeStyleLineAlignment"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство VstkResource. Получает или задает выравнивание линии стиля Stroke"
type: docs
weight: 80
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/
---
{{< psd/tize >}}
## VstkResource.StrokeStyleLineAlignment property

Получает или задает выравнивание линии стиля обводки.

```csharp
public StrokePosition StrokeStyleLineAlignment { get; set; }
```

## Примеры

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

### См. также

* enum [StrokePosition](../../../aspose.psd.fileformats.psd.layers.layereffects/strokeposition/)
* class [VstkResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../../)


