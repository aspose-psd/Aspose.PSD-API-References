---
title: UnitArrayStructure
second_title: Справочник по Aspose.PSD для .NET API
description: Определяет класс UnitArrayStructure который содержитDoubleмассив значений и их единицы измерения. Он используется в файловых ресурсах PSD обычноObjectArrayStructure./objectarraystructure.
type: docs
weight: 3160
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/
---
## UnitArrayStructure class

Определяет класс UnitArrayStructure, который содержитDoubleмассив значений и их единицы измерения. Он используется в файловых ресурсах PSD, обычно[`ObjectArrayStructure`](../objectarraystructure).

```csharp
public sealed class UnitArrayStructure : OSTypeStructure
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [UnitArrayStructure](unitarraystructure)(ClassID, UnitTypes, double[]) | Инициализирует новый экземпляр класса[`UnitArrayStructure`](../unitarraystructure). |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/key) { get; } | Получает ключ структуры этого единичного массива. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname) { get; set; } | Получает или задает имя ключа. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/length) { get; } | Получает[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)длину в байтах. |
| [UnitType](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/unittype) { get; set; } | Получает или задает тип единицы измерения для значений[`UnitArrayStructure`](../unitarraystructure). |
| [ValueCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/valuecount) { get; } | Получает количество значений. |
| [Values](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/values) { get; set; } | Получает или задает значения структуры единичного массива. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength)() | Получает длину заголовка. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save)(StreamContainer) | Сохраняет структуру в указанный контейнер потока. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname)(StreamContainer) | Сохраняет структуру в указанный контейнер потока. |

## Поля

| Имя | Описание |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/structurekey) | Определяет ключ 'UnFl'[`UnitArrayStructure`](../unitarraystructure). |

### Примеры

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

### Смотрите также

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
