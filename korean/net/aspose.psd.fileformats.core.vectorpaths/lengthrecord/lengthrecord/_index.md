---
title: "LengthRecord.LengthRecord"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "LengthRecord 생성자. LengthRecord 클래스의 새 인스턴스를 초기화합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/lengthrecord/
---
{{< psd/tize >}}
## LengthRecord(byte[]) {#constructor_1}

`[`LengthRecord`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public LengthRecord(byte[] data)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | Byte[] | 레코드 데이터입니다. |

### 또 보기

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)

---

## LengthRecord() {#constructor}

`[`LengthRecord`](../)` 클래스의 새 인스턴스를 초기화합니다.

```csharp
public LengthRecord()
```

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

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


