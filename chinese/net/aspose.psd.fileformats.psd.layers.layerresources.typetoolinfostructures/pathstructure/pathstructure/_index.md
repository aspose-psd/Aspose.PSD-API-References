---
title: PathStructure.PathStructure
second_title: Aspose.PSD for .NET API 参考
description: PathStructure 构造函数. 初始化一个新的实例PathStructure类.
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

初始化一个新的实例[`PathStructure`](../)类.

```csharp
public PathStructure(ClassID keyName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| keyName | ClassID | 密钥名称。 |

### 例子

以下代码演示了加载具有 PathStructure 结构的文件的能力。

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### 也可以看看

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* 部件 [Aspose.PSD](../../../)


