---
title: LengthRecord.ShapeIndex
second_title: .NET API 참조용 Aspose.PSD
description: LengthRecord 재산. 레이어에서 현재 경로 모양의 인덱스를 가져오거나 설정합니다.
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/shapeindex/
---
## LengthRecord.ShapeIndex property

레이어에서 현재 경로 모양의 인덱스를 가져오거나 설정합니다.

```csharp
public ushort ShapeIndex { get; set; }
```

### 예

다음 코드 예제는 새 LengthRecord 속성, PathOperations(부울 연산), ShapeIndex 및 BezierKnotRecordsCount의 지원을 보여줍니다.

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

    // 여기에서 도형을 결합하는 방법을 변경합니다.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### 또한보십시오

* class [LengthRecord](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Core.VectorPaths](../../lengthrecord/)
* 집회 [Aspose.PSD](../../../)


