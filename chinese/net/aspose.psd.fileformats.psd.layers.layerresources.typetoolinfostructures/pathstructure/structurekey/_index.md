---
title: "PathStructure.StructureKey"
second_title: "Aspose.PSD for .NET API 参考"
description: "PathStructure 字段。标识结构键"
type: docs
weight: 60
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/
---
{{< psd/tize >}}
## PathStructure.StructureKey field

识别结构键。

```csharp
public const int StructureKey;
```

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


