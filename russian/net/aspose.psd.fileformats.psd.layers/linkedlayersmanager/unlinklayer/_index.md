---
title: "LinkedLayersManager.UnlinkLayer"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод LinkedLayersManager. Отключает слой"
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/
---
{{< psd/tize >}}
## LinkedLayersManager.UnlinkLayer method

Отвязывает слой..

```csharp
public void UnlinkLayer(Layer layer)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| слой | Слой | Слой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Слой равен null. |
| ArgumentException | Контейнер слоя должен быть тем же, что и текущий PsdImage. |

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

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


