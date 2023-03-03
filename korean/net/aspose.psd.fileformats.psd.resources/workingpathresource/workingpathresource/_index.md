---
title: WorkingPathResource.WorkingPathResource
second_title: .NET API 참조용 Aspose.PSD
description: WorkingPathResource 건설자. 의 새 인스턴스를 초기화합니다.WorkingPathResource 클래스.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.resources/workingpathresource/workingpathresource/
---
## WorkingPathResource constructor

의 새 인스턴스를 초기화합니다.[`WorkingPathResource`](../) 클래스.

```csharp
public WorkingPathResource(byte[] dataBytes)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| dataBytes | Byte[] | 벡터 경로의 데이터입니다. |

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

* class [WorkingPathResource](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* 집회 [Aspose.PSD](../../../)


