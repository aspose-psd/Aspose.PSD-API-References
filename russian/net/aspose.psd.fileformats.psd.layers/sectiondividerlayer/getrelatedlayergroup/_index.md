---
title: "SectionDividerLayer.GetRelatedLayerGroup"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод SectionDividerLayer. Получает LayerGroup, связанный с этим экземпляром SectionDividerLayer"
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/getrelatedlayergroup/
---
{{< psd/tize >}}
## SectionDividerLayer.GetRelatedLayerGroup method

Получает [`LayerGroup`](../../layergroup/), связанный с этим экземпляром [`SectionDividerLayer`](../).

```csharp
public LayerGroup GetRelatedLayerGroup()
```

### Возвращаемое значение

Экземпляр [`LayerGroup`](../../layergroup/).

## Примеры

Следующий код демонстрирует слои SectionDividerLayer и как получить связанный с ними LayerGroup.

```csharp
[C#]

// Следующий код демонстрирует слои SectionDividerLayer и как получить связанный с ними LayerGroup.

// Иерархия слоёв
//    [0]: '</Layer group>' SectionDividerLayer для группы 1
//    [1]: 'Layer 1' Обычный слой
//    [2]: '</Layer group>' SectionDividerLayer для группы 2
//    [3]: '</Layer group>' SectionDividerLayer для группы 3
//    [4]: 'Group 3' GroupLayer
//    [5]: 'Group 2' GroupLayer
//    [6]: 'Group 1' GroupLayer

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // Создание иерархии слоёв
    // Добавить LayerGroup 'Group 1'
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Добавить обычный слой
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // Добавить LayerGroup 'Group 2'
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // Добавить LayerGroup 'Group 3'
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // Получает свойства SectionDividerLayer
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // используя метод SectionDividerLayer.GetRelatedLayerGroup(), получает связанный экземпляр LayerGroup.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // the same LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' contains 5 layers
}
```

### См. также

* class [LayerGroup](../../layergroup/)
* class [SectionDividerLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


