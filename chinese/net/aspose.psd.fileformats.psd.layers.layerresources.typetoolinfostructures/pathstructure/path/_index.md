---
title: "PathStructure.Path"
second_title: "Aspose.PSD for .NET API 参考"
description: "PathStructure 属性。获取或设置路径"
type: docs
weight: 40
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
{{< psd/tize >}}
## PathStructure.Path property

获取或设置路径。

```csharp
public string Path { get; set; }
```

### Property Value

完整路径。

## 示例

以下代码演示了使用 PathStructure 结构加载文件的能力。

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### 另请参阅

* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


