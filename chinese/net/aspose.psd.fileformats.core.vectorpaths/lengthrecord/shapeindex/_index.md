---
title: LengthRecord.ShapeIndex
second_title: Aspose.PSD for .NET API 参考
description: LengthRecord 财产. 获取或设置图层中当前路径形状的索引
type: docs
weight: 70
url: /zh/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/shapeindex/
---
## LengthRecord.ShapeIndex property

获取或设置图层中当前路径形状的索引。

```csharp
public ushort ShapeIndex { get; set; }
```

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

* class [LengthRecord](../)
* 命名空间 [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* 部件 [Aspose.PSD](../../../)


