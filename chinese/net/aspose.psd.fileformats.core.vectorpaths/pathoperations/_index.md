---
title: "枚举 PathOperations"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations 枚举。路径形状组合布尔运算的操作"
type: docs
weight: 1400
url: /zh/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
{{< psd/tize >}}
## PathOperations enumeration

路径形状组合的操作（布尔运算）。

```csharp
public enum PathOperations
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | 排除重叠形状（XOR 操作）。 |
| CombineShapes | `1` | 合并形状（OR 操作）。这是 Photoshop 中的默认值。 |
| SubtractFrontShape | `2` | 减去前置形状（NOT 操作）。 |
| IntersectShapeAreas | `3` | 相交形状区域（AND 操作）。 |

## 示例

以下代码示例演示了对新 LengthRecord 属性、PathOperations（布尔运算）、ShapeIndex 和 BezierKnotRecordsCount 的支持。

```csharp
[C#]

string sourceFilePath = "PathOperationsShape.psd";
string outputFilePath = "out_PathOperationsShape.psd";

using (var im = (PsdImage)Image.Load(sourceFilePath))
{
    VsmsResource resource = null;
    foreach (var layerResource in im.Layers[1].Resources)
    {
        if (layerResource is VsmsResource)
        {
            resource = (VsmsResource)layerResource;
            break;
        }
    }

    LengthRecord lengthRecord0 = (LengthRecord)resource.Paths[2];
    LengthRecord lengthRecord1 = (LengthRecord)resource.Paths[7];
    LengthRecord lengthRecord2 = (LengthRecord)resource.Paths[11];

    // 这里我们改变了形状之间的组合方式。
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


