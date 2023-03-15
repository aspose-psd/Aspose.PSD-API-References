---
title: Class MlstResource
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource сорт. Ресурс mlst. Этот класс помимо прочего содержит информацию о положении слоя на временной шкале.
type: docs
weight: 2830
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
## MlstResource class

Ресурс mlst. Этот класс, помимо прочего, содержит информацию о положении слоя на временной шкале.

```csharp
public class MlstResource : LayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MlstResource](mlstresource/)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | Получает или задает версию дескриптора. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | Получает или задает структуры. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/psdversion/) { get; } | Получает версию psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/signature/) { get; } | Получает подпись. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | Сохраняет указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | ВозвращаетString который представляет этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | Информационный ключ типа инструмента. |

### Примеры

Следующий код демонстрирует поддержку ресурса MlstResource, который предоставляет низкоуровневый механизм для управления состояниями слоя.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // Отключаем слой 1 на кадре 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### Смотрите также

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* сборка [Aspose.PSD](../../)


