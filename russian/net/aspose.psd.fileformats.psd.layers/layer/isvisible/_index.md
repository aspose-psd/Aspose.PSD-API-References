---
title: "Layer.IsVisible"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство Layer. Получает или задаёт значение, указывающее, видим ли слой"
type: docs
weight: 180
url: /ru/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

Получает или задает значение, указывающее, видим ли слой

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` если этот экземпляр видим; иначе `false`.

## Примеры

В следующем примере демонстрируется, как изменить видимость LayerGroup в Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// внесите изменения в имена слоёв и сохраните их
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Отключить всё внутри группы
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### См. также

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


