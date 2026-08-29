---
title: "Класс Lnk2Resource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk2Resource класс. Определяет класс, который содержит информацию о встроенных файлах в изображении формата PSD. Ресурс ссылки может содержать несколько экземпляров LiFdDataSource, к которым можно получить доступ через индексатор"
type: docs
weight: 3030
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---
{{< psd/tize >}}
## Lnk2Resource class

Определяет класс, который содержит информацию о встроенных файлах в изображении формата PSD. Ресурс ссылки может содержать несколько экземпляров [`LiFdDataSource`](../lifddatasource/) , к которым можно получить доступ через индексатор.

```csharp
public class Lnk2Resource : LinkResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Lnk2Resource](lnk2resource/)() | Инициализирует новый экземпляр класса `Lnk2Resource`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Получает количество источников данных ссылки, к которым можно получить доступ через индексатор. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Получает значение, указывающее, пустой ли этот экземпляр ресурса ссылки. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | Получает [`LiFdDataSource`](../lifddatasource/) по указанному индексу. (2 индексатора) |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Получает длину глобального ресурса ссылки PSD в байтах. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Сохраняет данные блока ресурса. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/typetoolkey/) | Ключ информации о типе инструмента. |

### См. также

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


