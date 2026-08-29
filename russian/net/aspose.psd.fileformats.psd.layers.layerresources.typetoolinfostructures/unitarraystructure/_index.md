---
title: "Класс UnitArrayStructure"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.UnitArrayStructure класс. Определяет класс UnitArrayStructure, который содержит массив значений Double и их единицу измерения. Обычно используется в ресурсах PSD‑файла, обычно объектом ObjectArrayStructure."
type: docs
weight: 3660
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/
---
{{< psd/tize >}}
## UnitArrayStructure class

Определяет класс UnitArrayStructure, который содержит массив значений Double и их единицу измерения. Используется в ресурсах PSD‑файла, обычно через [`ObjectArrayStructure`](../objectarraystructure/).

```csharp
public sealed class UnitArrayStructure : OSTypeStructure
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [UnitArrayStructure](unitarraystructure/)(ClassID, UnitTypes, double[]) | Инициализирует новый экземпляр класса `UnitArrayStructure`. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/key/) { get; } | Получает ключ этой структуры массива единиц. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Получает или задает имя ключа. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/length/) { get; } | Получает длину [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) в байтах. |
| [UnitType](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unittype/) { get; set; } | Получает или задает тип единицы измерения значений `UnitArrayStructure`. |
| [ValueCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/valuecount/) { get; } | Получает количество значений. |
| [Values](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/values/) { get; set; } | Получает или задает значения структуры массива единиц. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Получает длину заголовка. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Сохраняет структуру в указанный контейнер потока. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Сохраняет структуру в указанный контейнер потока. |

## Поля

| Имя | Описание |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/structurekey/) | Определяет ключ 'UnFl' для `UnitArrayStructure`. |

## Примеры

Следующий код демонстрирует поддержку подписей ObAr и UnFl.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    UnitArrayStructure verticalStructure = null;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as PlLdResource;
            if (resource != null && resource.IsCustom)
            {
                foreach (OSTypeStructure structure in resource.Items)
                {
                    if (structure.KeyName.ClassName == "customEnvelopeWarp")
                    {
                        AssertAreEqual(typeof(DescriptorStructure), structure.GetType());
                        var custom = (DescriptorStructure)structure;
                        AssertAreEqual(custom.Structures.Length, 1);
                        var mesh = custom.Structures[0];
                        AssertAreEqual(typeof(ObjectArrayStructure), mesh.GetType());
                        var meshObjectArray = (ObjectArrayStructure)mesh;
                        AssertAreEqual(meshObjectArray.Structures.Length, 2);
                        var vertical = meshObjectArray.Structures[1];
                        AssertAreEqual(typeof(UnitArrayStructure), vertical.GetType());
                        verticalStructure = (UnitArrayStructure)vertical;
                        AssertAreEqual(verticalStructure.UnitType, UnitTypes.Pixels);
                        AssertAreEqual(verticalStructure.ValueCount, 16);

                        break;
                    }
                }
            }
        }
    }

    AssertAreEqual(true, verticalStructure != null);
}
```

### См. также

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


