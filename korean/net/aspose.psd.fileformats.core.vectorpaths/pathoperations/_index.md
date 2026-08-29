---
title: "열거형 PathOperations"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations 열거형. 경로 형태를 결합하는 부울 연산에 대한 작업들"
type: docs
weight: 1400
url: /ko/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
{{< psd/tize >}}
## PathOperations enumeration

경로 형태 결합(불린 연산)을 위한 작업입니다.

```csharp
public enum PathOperations
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | 겹치는 형태 제외 (XOR 연산). |
| CombineShapes | `1` | 형태 결합 (OR 연산). 이는 Photoshop의 기본값입니다. |
| SubtractFrontShape | `2` | 앞 형태 빼기 (NOT 연산). |
| IntersectShapeAreas | `3` | 형태 영역 교집합 (AND 연산). |

## 예제

다음 코드 예제는 새로운 LengthRecord 속성, PathOperations(부울 연산), ShapeIndex 및 BezierKnotRecordsCount에 대한 지원을 보여줍니다.

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

    // 여기서는 형태 간 결합 방식을 변경합니다.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### 또 보기

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


