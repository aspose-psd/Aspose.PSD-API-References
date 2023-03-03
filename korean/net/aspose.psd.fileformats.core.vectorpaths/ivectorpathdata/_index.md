---
title: Interface IVectorPathData
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData 상호 작용. 벡터 경로 데이터에 액세스하기 위한 인터페이스입니다.
type: docs
weight: 1350
url: /ko/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
## IVectorPathData interface

벡터 경로 데이터에 액세스하기 위한 인터페이스입니다.

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

### 예

이 예는 자르기 작업의 올바른 작업을 위해 PsdImage.ImageResources에서 'WorkingPathResource' 리소스의 지원을 보여줍니다.

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

// 저장된 이미지를 불러와 변경 사항을 확인합니다.
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

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* 집회 [Aspose.PSD](../../)


