---
title: "LayerGroup.IsOpen"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство LayerGroup. Возвращает или задаёт, открыт ли каталог; если установлено в true, группа будет в открытом состоянии при запуске, иначе в свернутом состоянии."
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
{{< psd/tize >}}
## LayerGroup.IsOpen property

Получает или задает, открыт ли каталог; если установить `true`, группа будет в открытом состоянии при запуске, иначе — в свернутом.

```csharp
public bool IsOpen { get; set; }
```

## Примеры

Следующий код показывает, как открыть и закрыть LayerGroup (Folder) с помощью свойства IsOpen.

```csharp
[C#]

// Пример чтения и записи свойства IsOpen во время выполнения.
string sourceFileName = "LayerGroupOpenClose.psd";
string outputFileName = "OutputLayerGroupOpenClose.psd";

using (var image = (PsdImage) Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        if (layer is LayerGroup && layer.Name == "Group 1")
        {
            bool isOpenedGroup1 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup1;
        }

        if (layer is LayerGroup && layer.Name == "Group 2")
        {
            bool isOpenedGroup2 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup2;
        }
    }

    image.Save(outputFileName);
}
```

### См. также

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


