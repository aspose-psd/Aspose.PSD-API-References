---
title: PathStructure.Length
second_title: Aspose.PSD for .NET API 参考
description: PathStructure 财产. 获取OSTypeStructure字节长度.
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
## PathStructure.Length property

获取[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)字节长度.

```csharp
public override int Length { get; }
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


