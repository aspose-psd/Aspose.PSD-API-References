---
title: PathStructure.StructureKey
second_title: Aspose.PSD for .NET API 参考
description: PathStructure 场地. 标识结构键
type: docs
weight: 60
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/
---
## PathStructure.StructureKey field

标识结构键。

```csharp
public const int StructureKey;
```

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

* class [PathStructure](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* 部件 [Aspose.PSD](../../../)


