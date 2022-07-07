---
title: ObjectArrayStructure
second_title: Справочник по Aspose.PSD для .NET API
description: Инициализирует новый экземпляр классаObjectArrayStructureaspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure.
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/objectarraystructure/
---
## ObjectArrayStructure(string, string, OSTypeStructure[]) {#constructor_1}

Инициализирует новый экземпляр класса[`ObjectArrayStructure`](../../objectarraystructure).

```csharp
public ObjectArrayStructure(string keyName, string classIdName, OSTypeStructure[] structures)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| keyName | String | Имя ключа. |
| classIdName | String | Имя идентификатора класса. |
| structures | OSTypeStructure[] | Структуры. |

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

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
* class [ObjectArrayStructure](../../objectarraystructure)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../objectarraystructure)
* сборка [Aspose.PSD](../../../)

---

## ObjectArrayStructure(int, ClassID, ClassID, string, OSTypeStructure[]) {#constructor}

Инициализирует новый экземпляр класса[`ObjectArrayStructure`](../../objectarraystructure).

```csharp
public ObjectArrayStructure(int key, ClassID keyName, ClassID classID, string className, 
    OSTypeStructure[] structures)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | Int32 | Целочисленный ключ. |
| keyName | ClassID | Имя ключа. |
| classID | ClassID | Идентификатор класса. |
| className | String | Имя класса. |
| structures | OSTypeStructure[] | Структуры. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | classID равен null |

### Примеры

Следующий код демонстрирует поддержку ObAr и подписи UnFl.

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid)
* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
* class [ObjectArrayStructure](../../objectarraystructure)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../objectarraystructure)
* сборка [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
