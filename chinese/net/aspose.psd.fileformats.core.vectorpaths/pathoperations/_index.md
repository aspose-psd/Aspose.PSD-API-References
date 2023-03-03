---
title: Enum PathOperations
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations 枚举. 路径形状组合的操作布尔运算
type: docs
weight: 1390
url: /zh/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

路径形状组合的操作（布尔运算）。

```csharp
public enum PathOperations
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | 排除重叠形状（异或运算）。 |
| CombineShapes | `1` | 组合形状（或运算）。这是 Photoshop 中的默认值。 |
| SubtractFrontShape | `2` | 减去前形状（非操作）。 |
| IntersectShapeAreas | `3` | 相交形状区域（AND 运算）. |

### 例子

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

    // 这里我们改变了组合形状的方式。
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### 也可以看看

* 命名空间 [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* 部件 [Aspose.PSD](../../)


