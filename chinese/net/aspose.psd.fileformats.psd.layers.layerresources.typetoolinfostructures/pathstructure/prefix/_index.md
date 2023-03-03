---
title: PathStructure.Prefix
second_title: Aspose.PSD for .NET API 参考
description: PathStructure 财产. 获取或设置路径前缀
type: docs
weight: 50
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
## PathStructure.Prefix property

获取或设置路径前缀。

```csharp
public string Prefix { get; set; }
```

### 适当的价值

完整路径。

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


