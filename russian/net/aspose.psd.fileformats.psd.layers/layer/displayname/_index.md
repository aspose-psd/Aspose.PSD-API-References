---
title: "Layer.DisplayName"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство Layer. Возвращает или задает отображаемое имя слоя"
type: docs
weight: 110
url: /ru/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
{{< psd/tize >}}
## Layer.DisplayName property

Получает или задает отображаемое имя слоя.

```csharp
public string DisplayName { get; set; }
```

### Property Value

Отображаемое имя слоя.

## Примеры

Следующий пример демонстрирует возможность установить значение DisplayName, при котором имя слоя отображается корректно.

```csharp
[C#]

// внесите изменения в имена слоёв и сохраните их
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // установить новое значение в свойство DisplayName
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### См. также

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


