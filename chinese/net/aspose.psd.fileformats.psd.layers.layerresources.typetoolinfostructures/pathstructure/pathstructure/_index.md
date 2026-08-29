---
title: "PathStructure.PathStructure"
second_title: "Aspose.PSD for .NET API 参考"
description: "PathStructure 构造函数。初始化 PathStructure 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure constructor

初始化 [`PathStructure`](../) 类的新实例。

```csharp
public PathStructure(ClassID keyName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| keyName | ClassID | 键名。 |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


