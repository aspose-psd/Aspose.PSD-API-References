---
title: "PsdImage.AddLayerGroup"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод PsdImage. Добавляет группу слоёв"
type: docs
weight: 400
url: /ru/net/aspose.psd.fileformats.psd/psdimage/addlayergroup/
---
{{< psd/tize >}}
## PsdImage.AddLayerGroup method

Добавляет группу слоёв.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index, bool startBehaviour)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| groupName | String | Имя группы. |
| index | Int32 | Индекс слоя, после которого вставлять. |
| startBehaviour | Boolean | если установлено `true` [start behaviour], то группа будет открыта при запуске, иначе будет свернута. |

### Возвращаемое значение

Открытие группы слоев

### Исключения

| исключение | условие |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Индекс должен находиться в пределах количества слоёв |

### См. также

* class [LayerGroup](../../../aspose.psd.fileformats.psd.layers/layergroup/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


