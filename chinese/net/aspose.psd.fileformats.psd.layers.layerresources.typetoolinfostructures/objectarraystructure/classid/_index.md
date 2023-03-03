---
title: ObjectArrayStructure.ClassID
second_title: Aspose.PSD for .NET API 参考
description: ObjectArrayStructure 财产. 获取或设置对象数组类 ID
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classid/
---
## ObjectArrayStructure.ClassID property

获取或设置对象数组类 ID。

```csharp
public ClassID ClassID { get; set; }
```

### 适当的价值

对象数组类 ID.

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [ObjectArrayStructure](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../objectarraystructure/)
* 部件 [Aspose.PSD](../../../)


