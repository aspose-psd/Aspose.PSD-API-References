---
title: "PostResource.Levels"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство PostResource. Уровни слоя Posterize"
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/
---
{{< psd/tize >}}
## PostResource.Levels property

Уровни слоя Posterize.

```csharp
public short Levels { get; set; }
```

### Возвращаемое значение

Значение int Levels

## Примеры

Следующий код демонстрирует возможность манипулирования PostResource.

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];

    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is PostResource)
        {
            ((PostResource)resource).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### См. также

* class [PostResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


