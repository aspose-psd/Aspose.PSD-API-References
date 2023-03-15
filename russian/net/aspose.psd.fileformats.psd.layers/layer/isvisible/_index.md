---
title: Layer.IsVisible
second_title: Справочник по Aspose.PSD для .NET API
description: Layer свойство. Получает или задает значение указывающее виден ли слой
type: docs
weight: 170
url: /ru/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
## Layer.IsVisible property

Получает или задает значение, указывающее, виден ли слой

```csharp
public bool IsVisible { get; set; }
```

### Стоимость имущества

`истинный` если этот экземпляр виден; в противном случае,`ЛОЖЬ` .

### Примеры

В следующем примере показано, как можно изменить видимость LayerGroup в Aspose.PSD.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// вносим изменения в имена слоев и сохраняем их
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Отключаем все внутри группы
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Смотрите также

* class [Layer](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* сборка [Aspose.PSD](../../../)


