---
title: "Класс LinkResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource класс. Определяет класс LinkResource, который содержит информацию о связанных или встроенных файлах в изображении формата PSD. Ресурс ссылки может содержать несколько экземпляров LinkDataSource, к которым можно получить доступ через индексаторы в любом производном классе."
type: docs
weight: 3010
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
{{< psd/tize >}}
## LinkResource class

Определяет класс LinkResource, который содержит информацию о связанных или встроенных файлах в изображении формата PSD. Ресурс ссылки может содержать несколько [`LinkDataSource`](../linkdatasource/) экземпляров, к которым можно получить доступ через индексаторы в любом производном классе.

```csharp
public abstract class LinkResource : LayerResource
```

## Свойства

| Имя | Описание |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Получает количество источников данных ссылки, к которым можно получить доступ через индексатор. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Получает значение, указывающее, пустой ли этот экземпляр ресурса ссылки. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Получает [`LinkDataSource`](../linkdatasource/) по указанному индексу, который является уникальным идентификатором источника данных ссылки. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Получает длину глобального ресурса ссылки PSD в байтах. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Сохраняет данные блока ресурса. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

### См. также

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


