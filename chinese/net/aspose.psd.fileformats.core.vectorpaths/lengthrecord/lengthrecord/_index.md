---
title: "LengthRecord.LengthRecord"
second_title: "Aspose.PSD for .NET API 参考"
description: "LengthRecord 构造函数。初始化 LengthRecord 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
{{< psd/tize >}}
## LengthRecord(byte[]) {#constructor_1}

初始化一个 [`LengthRecord`](../) 类的新实例。

```csharp
public LengthRecord(byte[] data)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | Byte[] | 记录数据。 |

### 另请参阅

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

初始化一个 [`LengthRecord`](../) 类的新实例。

```csharp
public LengthRecord()
```

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

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


