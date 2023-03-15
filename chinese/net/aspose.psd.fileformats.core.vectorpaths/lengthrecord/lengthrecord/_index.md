---
title: LengthRecord.LengthRecord
second_title: Aspose.PSD for .NET API 参考
description: LengthRecord 构造函数. 初始化一个新的实例LengthRecord类.
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
## LengthRecord(byte[]) {#constructor_1}

初始化一个新的实例[`LengthRecord`](../)类.

```csharp
public LengthRecord(byte[] data)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| data | Byte[] | 记录数据。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| !:PsdImageArgumentException | LengthRecord 创建的数据不正确 |

### 也可以看看

* class [LengthRecord](../)
* 命名空间 [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* 部件 [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

初始化一个新的实例[`LengthRecord`](../)类.

```csharp
public LengthRecord()
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


