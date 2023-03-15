---
title: Enum PathOperations
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations 열거형. 경로 모양 결합 작업부울 연산.
type: docs
weight: 1390
url: /ko/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

경로 모양 결합 작업(부울 연산).

```csharp
public enum PathOperations
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | 겹치는 도형 제외(XOR 연산). |
| CombineShapes | `1` | 도형 결합(OR 연산). 이것은 Photoshop의 기본값입니다. |
| SubtractFrontShape | `2` | 전면 모양 빼기(작업 아님). |
| IntersectShapeAreas | `3` | 모양 영역 교차(AND 연산). |

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

* 네임스페이스 [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* 집회 [Aspose.PSD](../../)


