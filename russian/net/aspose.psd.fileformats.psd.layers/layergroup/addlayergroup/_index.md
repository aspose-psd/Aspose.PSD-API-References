---
title: LayerGroup.AddLayerGroup
second_title: Справочник по Aspose.PSD для .NET API
description: LayerGroup метод. Добавляет группу слоев.
type: docs
weight: 70
url: /ru/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
## LayerGroup.AddLayerGroup method

Добавляет группу слоев.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| groupName | String | Название группы. |
| index | Int32 | Индекс слоя для вставки после. |

### Возвращаемое значение

Открытие группового слоя

### Примеры

В следующем примере показано добавление LayerGroup в другую LayerGroup.

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// создаем иерархию слоев следующим образом:
// -Группа 1
// --Слой 1
// --Группа 2
// ---Слой 2
// ---Слой 3
// --Слой 4

var createOptions = new PsdOptions();
createOptions.Source = new FileCreateSource(sourceFileName, false);
createOptions.Palette = new PsdColorPalette(new Color[] { Color.Green });

using (var psdImage = (PsdImage)Image.Create(createOptions, 500, 500))
{
    LayerGroup group1 = psdImage.AddLayerGroup("Group 1", 0, false);

    Layer layer1 = new Layer(psdImage);
    layer1.Name = "Layer 1";
    group1.AddLayer(layer1);

    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);

    Layer layer2 = new Layer(psdImage);
    layer2.Name = "Layer 2";
    group2.AddLayer(layer2);

    Layer layer3 = new Layer(psdImage);
    layer3.Name = "Layer 3";
    group2.AddLayer(layer3);

    Layer layer4 = new Layer(psdImage);
    layer4.Name = "Layer 4";
    group1.AddLayer(layer4);

    psdImage.Save();
}
```

### Смотрите также

* class [LayerGroup](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* сборка [Aspose.PSD](../../../)


