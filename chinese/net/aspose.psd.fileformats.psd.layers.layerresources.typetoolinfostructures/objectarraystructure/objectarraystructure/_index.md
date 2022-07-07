---
title: ObjectArrayStructure
second_title: Aspose.PSD for .NET API 参考
description: 初始化ObjectArrayStructureaspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure类的新实例
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/objectarraystructure/
---
## ObjectArrayStructure(string, string, OSTypeStructure[]) {#constructor_1}

初始化[`ObjectArrayStructure`](../../objectarraystructure)类的新实例。

```csharp
public ObjectArrayStructure(string keyName, string classIdName, OSTypeStructure[] structures)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| keyName | String | 密钥的名称。 |
| classIdName | String | 类标识符的名称。 |
| structures | OSTypeStructure[] | 结构。 |

### 例子

以下代码演示了对 ObAr 和 UnFl 签名的支持。

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

### 也可以看看

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
* class [ObjectArrayStructure](../../objectarraystructure)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../objectarraystructure)
* 部件 [Aspose.PSD](../../../)

---

## ObjectArrayStructure(int, ClassID, ClassID, string, OSTypeStructure[]) {#constructor}

初始化[`ObjectArrayStructure`](../../objectarraystructure)类的新实例。

```csharp
public ObjectArrayStructure(int key, ClassID keyName, ClassID classID, string className, 
    OSTypeStructure[] structures)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| key | Int32 | 整数键。 |
| keyName | ClassID | 密钥名称。 |
| classID | ClassID | 类标识符。 |
| className | String | 类的名称。 |
| structures | OSTypeStructure[] | 结构。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | classID 为 null |

### 例子

以下代码演示了对 ObAr 和 UnFl 签名的支持。

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

### 也可以看看

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid)
* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
* class [ObjectArrayStructure](../../objectarraystructure)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../objectarraystructure)
* 部件 [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
