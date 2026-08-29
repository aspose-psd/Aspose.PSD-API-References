---
title: "Класс LinkedLayersManager"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LinkedLayersManager класс. Класс менеджера связанных слоёв"
type: docs
weight: 3800
url: /ru/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---
{{< psd/tize >}}
## LinkedLayersManager class

Класс менеджера связанных слоёв.

```csharp
public sealed class LinkedLayersManager
```

## Методы

| Имя | Описание |
| --- | --- |
| [GetLayersByLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/)(short) | Получает слои по идентификатору группы ссылок. |
| [GetLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/)(Layer) | Получает идентификатор группы ссылок, связанный со слоем. |
| [LinkLayers](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/)(Layer[]) | Связывает входные слои и возвращает LingGroupId. |
| [UnlinkLayer](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/)(Layer) | Отвязывает слой.. |

## Примеры

Следующий пример демонстрирует, как можно управлять связанными слоями в Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Загрузите существующее изображение в экземпляр класса PsdImage
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // свяжите все слои в одну связанную группу
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // получает идентификатор для одного слоя
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // получает все связанные слои по идентификатору группы ссылок.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // отвяжите каждый слой от группы
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // возвращает NULL для идентификатора группы ссылок, в которой нет слоёв.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### См. также

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


