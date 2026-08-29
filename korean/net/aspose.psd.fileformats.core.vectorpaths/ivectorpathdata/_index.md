---
title: "인터페이스 IVectorPathData"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData 인터페이스. 벡터 경로 데이터에 액세스하기 위한 인터페이스"
type: docs
weight: 1360
url: /ko/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
{{< psd/tize >}}
## IVectorPathData interface

벡터 경로 데이터에 접근하기 위한 인터페이스입니다.

```csharp
public interface IVectorPathData
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | 이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | 이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | 이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | 경로 레코드를 가져오거나 설정합니다. |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | 버전을 가져오거나 설정합니다. |

## 예제

이 예제는 Crop 작업이 올바르게 작동하도록 PsdImage.ImageResources에서 'WorkingPathResource' 리소스 지원을 보여줍니다.

```csharp
[C#]

// 이미지를 자르고 저장합니다.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // WorkingPathResource 리소스를 검색합니다.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 2572506 || record.Points[0].Y != 8535408)
    {
        throw new Exception("Values is incorrect.");
    }

    // 자르고 저장합니다.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// 저장된 이미지를 로드하고 변경 사항을 확인합니다.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // WorkingPathResource 리소스를 검색합니다.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 4630510 || record.Points[0].Y != 22761088)
    {
        throw new Exception("Values is incorrect.");
    }
}
```

### 또 보기

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


