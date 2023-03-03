---
title: UnitArrayStructure.Values
second_title: Aspose.PSD for .NET API 参考
description: UnitArrayStructure 财产. 获取或设置单元数组结构值
type: docs
weight: 60
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/values/
---
## UnitArrayStructure.Values property

获取或设置单元数组结构值。

```csharp
public double[] Values { get; set; }
```

### 适当的价值

单位数组结构值。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 值属性不能为空。 |

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

* class [UnitArrayStructure](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../unitarraystructure/)
* 部件 [Aspose.PSD](../../../)


