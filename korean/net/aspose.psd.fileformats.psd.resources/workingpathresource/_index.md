---
title: "클래스 WorkingPathResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Resources.WorkingPathResource 클래스. 작업 경로 리소스"
type: docs
weight: 4450
url: /ko/net/aspose.psd.fileformats.psd.resources/workingpathresource/
---
{{< psd/tize >}}
## WorkingPathResource class

작업 경로 리소스.

```csharp
public sealed class WorkingPathResource : ResourceBlock, IVectorPathData
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [WorkingPathResource](workingpathresource/)(byte[]) | 새 `WorkingPathResource` 클래스 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/workingpathresource/datasize/) { get; } | 리소스 데이터 크기를 바이트 단위로 가져옵니다. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| [IsDisabled](../../aspose.psd.fileformats.psd.resources/workingpathresource/isdisabled/) { get; set; } | 이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [IsInverted](../../aspose.psd.fileformats.psd.resources/workingpathresource/isinverted/) { get; set; } | 이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.resources/workingpathresource/isnotlinked/) { get; set; } | 이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/workingpathresource/minimalversion/) { get; } | 필요한 최소 PSD 버전을 가져옵니다. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | 리소스 이름을 가져오거나 설정합니다. Pascal 문자열이며, 크기를 짝수로 맞추기 위해 패딩됩니다(널 이름은 0 두 바이트로 구성됩니다). |
| [Paths](../../aspose.psd.fileformats.psd.resources/workingpathresource/paths/) { get; set; } | 경로 레코드를 가져오거나 설정합니다. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | 리소스 서명을 가져옵니다. 항상 '8BIM'이어야 합니다. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | 데이터를 포함한 리소스 블록 크기를 바이트 단위로 가져옵니다. |
| [Version](../../aspose.psd.fileformats.psd.resources/workingpathresource/version/) { get; set; } | 버전을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 지정된 스트림에 리소스 블록을 저장합니다. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | 리소스 값을 검증합니다. |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


