---
title: LinkedLayersManager.LinkLayers
second_title: Справочник по Aspose.PSD для .NET API
description: LinkedLayersManager метод. Связывает входные слои и возвращает LingGroupId.
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/
---
## LinkedLayersManager.LinkLayers method

Связывает входные слои и возвращает LingGroupId.

```csharp
public short LinkLayers(Layer[] layers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| layers | Layer[] | Слои. |

### Возвращаемое значение

Идентификатор группы ссылок.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Слои нулевые. |
| ArgumentException | Количество слоев должно быть больше 1. |
| ArgumentException | Контейнер каждого слоя должен быть таким же, как текущий PsdImage. |

### Примеры

В следующем примере показано, как вы можете манипулировать связанными слоями в Aspose.PSD.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Загружаем существующее изображение в экземпляр класса PsdImage
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // связываем все слои в одну связанную группу
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // получаем id для одного слоя
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // получает все связанные слои по идентификатору группы ссылок.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // отвязать каждый слой от группы
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // возвращает NULL для идентификатора группы ссылок, в которой нет слоев в группе.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Смотрите также

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* сборка [Aspose.PSD](../../../)


