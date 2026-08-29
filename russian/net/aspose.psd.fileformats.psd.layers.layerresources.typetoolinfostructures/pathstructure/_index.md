---
title: "Класс PathStructure"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.PathStructure класс. Структура пути."
type: docs
weight: 3610
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/
---
{{< psd/tize >}}
## PathStructure class

Структура пути.

```csharp
public sealed class PathStructure : OSTypeStructure
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PathStructure](pathstructure/)(ClassID) | Инициализирует новый экземпляр класса `PathStructure`. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/) { get; } | Получает ключ структуры. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Получает или задает имя ключа. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/) { get; } | Получает длину [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) в байтах. |
| [Path](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/) { get; set; } | Получает или задает путь. |
| [Prefix](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/) { get; set; } | Получает или задает префикс пути. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Получает длину заголовка. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Сохраняет структуру в указанный контейнер потока. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Сохраняет структуру в указанный контейнер потока. |

## Поля

| Имя | Описание |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/) | Определяет ключ структуры. |

## Примеры

Следующий код демонстрирует возможность загрузки файла со структурой PathStructure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### См. также

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


